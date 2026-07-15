# llm-nvim

> You are working in a project that follows a strict Task Documentation System.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/llm-nvim/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Cursor Rules

You are working in a project that follows a strict Task Documentation System.

## Task System
- **Source of Truth**: The `docs/tasks/` directory contains the state of all work.
- **Workflow**:
    1. Check context: `./scripts/tasks context`
    2. Create task if needed: `./scripts/tasks create ...`
    3. Update status: `./scripts/tasks update ...`
- **Reference**: See `docs/tasks/GUIDE.md` for details.

## Tools
- Use `./scripts/tasks` for all task operations.
- Use `--format json` if you need to parse output.

---
> Source: [julwrites/llm-nvim](https://github.com/julwrites/llm-nvim) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-07-15 -->
