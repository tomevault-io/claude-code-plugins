# linting

> When you have made edits run the following commands to lint the code:

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/linting/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


When you have made edits run the following commands to lint the code:

```bash
ruff format .
ruff check . --fix
```

This will format the code and attempt to fix any linting errors automatically.

---
> Source: [Hankanman/Area-Occupancy-Detection](https://github.com/Hankanman/Area-Occupancy-Detection) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-18 -->
