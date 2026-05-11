# ralph

> 1. Load prd.json → first "todo" story

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/ralph/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# RALPH

- PAUSED: false

## Loop
1. Load prd.json → first "todo" story
2. Implement minimal change
3. Run guard: bash scripts/ralph/guard.sh scripts/ralph/constraints.json
4. Commit + push

## Commands
- Tests: echo "No tests configured"

---
> Source: [acoyfellow/ralph](https://github.com/acoyfellow/ralph) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-04 -->
