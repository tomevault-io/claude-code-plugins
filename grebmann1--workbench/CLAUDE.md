# agent-types-and-safety

> Preserve strong types and distinguish real type checks from weaker signals

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/agent-types-and-safety/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# Agent Types And Safety

- Prefer existing types, validated data shapes, and shared helpers over ad hoc inline types or duplicated type logic.
- Avoid introducing `any`, wide casts, or weaker return types unless the local codebase pattern truly requires it.
- When you touch typed code, use the closest real typecheck or TypeScript build command for that package when one exists.
- Do not claim full TypeScript verification from a green lint pass or successful bundle alone.
- In areas with weak or partial typing coverage, call out the remaining risk instead of overstating confidence.

---
> Source: [grebmann1/workbench](https://github.com/grebmann1/workbench) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-06-15 -->
