# consola

> This project uses consola for logging with a globally configured log level.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/consola/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# Logging

- Use `consola` (from `consola`), not `console`. Log level is set from runtime config in `app/plugins/01.logging.ts`. In tests that touch code using consola, mock `consola` (see `test/nuxt/app/plugins/01.logging.test.ts`).

---
> Source: [Wetzel402/Skylite-UX](https://github.com/Wetzel402/Skylite-UX) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-19 -->
