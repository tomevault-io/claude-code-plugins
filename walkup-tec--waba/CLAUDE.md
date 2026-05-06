# ucp-supabase-migrations-sql

> Supabase migrations SQL - RLS, idempotência e segurança

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/ucp-supabase-migrations-sql/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# Supabase Migrations SQL UCP

Ao editar `supabase/migrations/**/*.sql`:

- Evite `DROP`/`ALTER` destrutivos sem estratégia (backups, janelas, migração reversível quando possível).
- Preservar RLS: garanta que `Row Level Security` e policies continuem corretas após mudanças.
- Use transações quando apropriado para manter consistência.
- Padronize nomes de constraints/índices e crie índices alinhados a filtros comuns (incluindo `tenant_id` se existir).
- Não introduza seeds com dados sensíveis.

---
> Source: [walkup-tec/waba](https://github.com/walkup-tec/waba) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-04-30 -->
