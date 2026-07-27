# brownie

> All agents must follow these rules:

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/brownie/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Agent Requirements

All agents must follow these rules:

brownie is always compiled. PyPI wheels are compiled, setup compiles the project, and tests/CI must validate compiled extensions. Do not invent or reason from an interpreted `.py` runtime path; tracked `.py` files are mypyc source inputs.

---
> Source: [eth-brownie/brownie](https://github.com/eth-brownie/brownie) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-07-21 -->
