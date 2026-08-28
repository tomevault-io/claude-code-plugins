# 000-project

> Project architectural overview, shell commands, and agent guidelines for open-agent-engine

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/000-project/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# open-agent-engine Architectural Guidelines

> Cross-platform multi-agent scaffolding, skill package manager, and transpiler engine

## Shell Commands
- Build: `pnpm build`
- Test: `pnpm test`
- Typecheck: `pnpm typecheck`
- Dev: `pnpm dev`

## Operational Boundaries
- Always execute tests and type verification before committing code changes.
- Adhere to modular boundary contracts across packages.

---
> Source: [jedmamosto/open-agent-engine](https://github.com/jedmamosto/open-agent-engine) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-08-28 -->
