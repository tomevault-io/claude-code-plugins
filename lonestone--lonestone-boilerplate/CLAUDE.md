# 5-migrations

> Working or creating database migrations

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/5-migrations/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

Migrations should be created using the `mikro-orm` CLI, after modifying any entity file.

```bash
cd apps/api
pnpm db:migrate:create
```

---
> Source: [lonestone/lonestone-boilerplate](https://github.com/lonestone/lonestone-boilerplate) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-28 -->
