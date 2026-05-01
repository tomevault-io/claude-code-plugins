# arktype-usage

> When you would otherwise reach for Zod, use Arktype. Read this any time you need to work with Arktype

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/arktype-usage/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# Arktype Usage Guidelines

This rulecard is intentionally short. For examples and edge cases, see `docs/reference/arktype-usage.md`.

## Rules of thumb

- Use optional keys via `'key?'` (not `string | undefined`).
- Use `type({ '[string]': Schema })` for records.
- Use `Schema.array()` for arrays (avoid tuple mistakes).

---
> Source: [prisma/prisma-next](https://github.com/prisma/prisma-next) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-04-20 -->
