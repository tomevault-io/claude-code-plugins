# telegram-tracking-app

> Folder conventions — repository for DB access, usecase for business logic

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/telegram-tracking-app/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# Folder Conventions

## `src/repository/`

All **database access** code lives here. A repository:
- Talks directly to Supabase (queries, inserts, updates, deletes)
- Returns domain types — never raw Supabase responses
- Has no business logic

```typescript
// src/repository/transaction.repository.ts
export const transactionRepository = {
  async findByUserId(userId: number): Promise<Transaction[]> {
    const { data, error } = await supabase
      .from('transactions')
      .select('*')
      .eq('user_id', userId);
    if (error) throw error;
    return data;
  },
};
```

## `src/usecase/`

All **business logic** lives here. A use case:
- Orchestrates one or more repositories
- Contains validation, rules, and side-effects (e.g. Telegram messages)
- Has no direct Supabase calls — delegates to repositories

```typescript
// src/usecase/add-transaction.usecase.ts
export async function addTransactionUseCase(input: AddTransactionInput) {
  const fundSource = await fundSourceRepository.findById(input.fundSourceId);
  if (!fundSource?.is_active) throw new Error('Fund source is inactive');

  const transaction = await transactionRepository.create(input);
  await fundSourceBalanceRepository.increment(input.fundSourceId, input.amount);
  return transaction;
}
```

## Rule

| Concern | Folder |
|---|---|
| Supabase queries / DB access | `src/repository/` |
| Business rules / orchestration | `src/usecase/` |
| API routes / bot handlers | `src/app/` or `src/lib/bot.ts` |

---
> Converted and distributed by [TomeVault](https://tomevault.io/claim/ferdinand066)
> This is a context snippet only. You'll also want the standalone SKILL.md file — [download at TomeVault](https://tomevault.io/claim/ferdinand066)
<!-- tomevault:4.0:claude_md:2026-04-09 -->
