# pi-markdown-workflows

> Pi extension that provides workflow tooling (`workflows`, `workflows_create`, `/workflow`) and embedded subdirectory `AGENTS.md` autoloading.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/pi-markdown-workflows/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# AGENTS.md

## Repository Overview

Pi extension that provides workflow tooling (`workflows`, `workflows_create`, `/workflow`) and embedded subdirectory `AGENTS.md` autoloading.

## Build & Verification

- Typecheck: `npx tsc --noEmit`
- Build: `npm run build`

## Notes

- Workflow storage path: `./.pi/workflows/<slug>/SKILL.md`
- Do not edit `dist/` manually.

---
> Source: [IgorWarzocha/pi-markdown-workflows](https://github.com/IgorWarzocha/pi-markdown-workflows) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-04 -->
