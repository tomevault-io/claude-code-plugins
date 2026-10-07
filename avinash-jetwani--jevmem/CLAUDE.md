# jevmem

> 1. Migrations live in db/migrations and run with pnpm db:migrate.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/jevmem/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Agent notes

1. Migrations live in db/migrations and run with pnpm db:migrate.
2. Use pnpm for every install; npm lockfiles are rejected in review.

## Jevmem project memory

Durable project memory lives in `JEVMEM.md` and is served by the `jevmem` MCP server.

- Before any non-trivial task, call the `search_memory` tool.

## Testing

- Integration tests need Docker running locally.

---
> Source: [Avinash-jetwani/jevmem](https://github.com/Avinash-jetwani/jevmem) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-10-06 -->
