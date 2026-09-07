# agentsmd-gen

> This repository contains `agents-gen`, an Agent Skill that creates and maintains scoped project `AGENTS.md` files from repository evidence.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/agentsmd-gen/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Project

This repository contains `agents-gen`, an Agent Skill that creates and maintains scoped project `AGENTS.md` files from repository evidence.

## Verification

- Validate the Skill: `python3 "${CODEX_HOME:-$HOME/.codex}/skills/.system/skill-creator/scripts/quick_validate.py" agents-gen`
- Run tests: `python3 -m unittest discover -s agents-gen/tests -v`

---
> Source: [Niall-Young/AgentsMD-GEN](https://github.com/Niall-Young/AgentsMD-GEN) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-09-07 -->
