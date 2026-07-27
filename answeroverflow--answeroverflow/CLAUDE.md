# answeroverflow

> Prefer yield* for accessing Effect dependencies instead of passing them as function arguments

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/answeroverflow/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# Effect Dependency Injection

**Prefer `yield* Dependency`** over passing dependencies as function arguments.

## ❌ Avoid

```typescript
const getUser = (db: Database, userId: string) =>
  Effect.gen(function* () {
    return yield* db.query("users", userId);
  });
```

## ✅ Prefer

```typescript
const getUser = (userId: string) =>
  Effect.gen(function* () {
    const db = yield* Database;
    return yield* db.query("users", userId);
  });
```

## Last Resort: When to Pass as Arguments

- Interfacing with non-Effect code
- Dynamic implementation selection at runtime
- Measured performance-critical paths

---
> Source: [AnswerOverflow/AnswerOverflow](https://github.com/AnswerOverflow/AnswerOverflow) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-07-26 -->
