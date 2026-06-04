# gm2godot

> - When Python or generated-code logic changes, run `./venv/bin/pyright --warnings` and fix every reported error or warning before considering the code change complete.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/gm2godot/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Project Instructions

- When Python or generated-code logic changes, run `./venv/bin/pyright --warnings` and fix every reported error or warning before considering the code change complete.
- Do not leave new Pylance/Pyright diagnostics, lint errors, or warnings in changed code.
- Run the relevant tests after lint/type-check fixes when code behavior changes. For broad code changes, run `./venv/bin/python -m unittest`.
- Do not run Pyright or tests for documentation-only changes unless the user explicitly asks for verification.

---
> Source: [Infiland/GM2Godot](https://github.com/Infiland/GM2Godot) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-06-04 -->
