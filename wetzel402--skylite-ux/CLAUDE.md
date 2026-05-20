# lint

> Lint rules are defined in eslint.config.mjs

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/lint/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# Lint

- ESLint config: `eslint.config.mjs` (antfu + Nuxt). Key rules: use `type` not `interface` (`ts/consistent-type-definitions`); no `any` (`ts/no-explicit-any`); no `console`—use consola (`no-console`); no `process.env`—use runtime config (`node/no-process-env`); `perfectionist/sort-imports`; filenames in camelCase with listed exceptions (`unicorn/filename-case`).

---
> Source: [Wetzel402/Skylite-UX](https://github.com/Wetzel402/Skylite-UX) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-19 -->
