# data-model

> Keep docs/DATA_MODEL.md updated when schema or RLS changes

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/data-model/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# Data model documentation

Canonical reference: [`docs/DATA_MODEL.md`](../../docs/DATA_MODEL.md)

Update when changing:

- SQL migrations (`supabase/migrations/`)
- RLS policies or household scope
- TypeScript models in `src/types/models.ts`
- Table/column usage in services that reflects schema changes

Add a migration summary row and a **Changelog** entry with the date.

Keep `src/types/models.ts` aligned with the latest migration.

---
> Source: [cameronconspm/Listio](https://github.com/cameronconspm/Listio) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-08-22 -->
