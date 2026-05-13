# agent-tui

> Before saying that work is complete, run these checks from the repository root:

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/agent-tui/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Agent Instructions

Before saying that work is complete, run these checks from the repository root:

```bash
bunx tsc --noEmit
bun run test
bun run format:check
bun run lint
```

If a check cannot be run, mention that explicitly in the final response.

---
> Source: [lgrammel/agent-tui](https://github.com/lgrammel/agent-tui) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-13 -->
