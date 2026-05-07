# 02-workflow

> Route work through commands, agents, and skills before improvising.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/02-workflow/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


Preferred routing order:
1. Resolve to a shared command in `commands/` when possible.
2. Use `agents/` to determine role ownership.
3. Use `skills/` to execute the workflow reliably.
4. Use `hooks/` and `scripts/hooks/` for automation and summaries.

Always keep docs, QA, telemetry, and release implications explicit when they are affected.

---
> Source: [MRCalderon3D/everything-game-dev-code](https://github.com/MRCalderon3D/everything-game-dev-code) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-03 -->
