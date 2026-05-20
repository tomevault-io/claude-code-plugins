# timestamps

> We store timestamps in UTC and use the global TZ when converting timestamps

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/timestamps/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# Timestamps

- Store datetimes in UTC in the database (Prisma `DateTime`).
- When converting for display or APIs, use the app's global timezone (or user TZ if added later). Use `date-fns` with UTC helpers / TZ when formatting.

---
> Source: [Wetzel402/Skylite-UX](https://github.com/Wetzel402/Skylite-UX) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-19 -->
