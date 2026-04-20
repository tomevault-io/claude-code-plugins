# clawith

> This file is the project-level entry point for agent instructions.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/clawith/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Clawith Project Instructions

This file is the project-level entry point for agent instructions.

## Primary Source of Project Rules

For this repository, the canonical project instructions live under:

- `.agents/rules/`
- `.agents/workflows/`

When working in this project, read and follow those files first. If this file and a file under `.agents/` ever conflict, prefer the more specific file under `.agents/`.

## Required Read Order

At the start of work on Clawith, use this order:

1. `.agents/workflows/read_architecture.md`
2. Relevant files under `.agents/rules/`

In practice:

- For general design, implementation, or feature questions, read `.agents/rules/design_and_dev.md`
- For deployment and environment updates, read `.agents/rules/deploy.md`
- For GitHub-related work, read `.agents/rules/github.md`
- For versioning and release work, read `.agents/rules/release.md`

## Notes

- The architecture document currently present in this repository is `ARCHITECTURE_SPEC_EN.md`
- Do not invent alternative instruction filenames when the real rules already exist under `.agents/`

---
> Source: [dataelement/Clawith](https://github.com/dataelement/Clawith) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-04-19 -->
