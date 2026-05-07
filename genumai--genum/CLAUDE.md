# web-rules

> We use different types of authorization depending on the instance type:

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/web-rules/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


## Tech stack

- React v18
- React router v7

## API for frontend

We use different types of authorization depending on the instance type:
- local instance uses http cookies
- cloud instance uses auth0 SPA

## Styling

- We use Tailwind CSS

## Environment

- We use Runtime Configuration System. DO NOT import env as meta.env. Use [runtime-config.ts](mdc:apps/web/src/lib/runtime-config.ts)

---
> Source: [GenumAI/genum](https://github.com/GenumAI/genum) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-02 -->
