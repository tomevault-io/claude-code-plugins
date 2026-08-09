# communique

> When AI contributes GitHub content—including a pull request description, review, pull request

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/communique/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Communiqué Development Guide

## GitHub Interactions

When AI contributes GitHub content—including a pull request description, review, pull request
comment, or discussion post—append this disclosure:

`*AI-assisted — Tool: <tool>; model: <provider>/<model>; version: <version-or-unavailable>.*`

Use the exact model and version identifiers exposed by the runtime. Never infer or guess them; use
`unavailable` when either value is not exposed.

---
> Source: [jdx/communique](https://github.com/jdx/communique) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-08-09 -->
