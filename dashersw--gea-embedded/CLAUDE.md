# gea-embedded

> - Do not run tests, builds, formatters, package installs, or dev servers unless the user explicitly asks.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/gea-embedded/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Agent Instructions

## Verification Policy

- Do not run tests, builds, formatters, package installs, or dev servers unless the user explicitly asks.
- If verification seems necessary, ask the user first and briefly explain why.
- For code changes, inspect the diff and report what was changed, along with any tests or builds that were not run.
- Prefer targeted inspection over broad verification unless the user approves a broader check.

---
> Source: [dashersw/gea-embedded](https://github.com/dashersw/gea-embedded) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-04-30 -->
