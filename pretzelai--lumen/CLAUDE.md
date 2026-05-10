# run-typecheck

> When you manually want to run a typecheck, you must:

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/run-typecheck/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


When you manually want to run a typecheck, you must:
`cd api && tsc --noEmit <file>`

This is because the `api` folder is a subproject in the monorepo

---
> Source: [pretzelai/lumen](https://github.com/pretzelai/lumen) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-06 -->
