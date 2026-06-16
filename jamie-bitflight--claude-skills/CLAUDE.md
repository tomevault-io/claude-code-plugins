# backlog-before-work

> When you identify work needs multiple steps/jobs, create backlog items — don't just describe them

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/backlog-before-work/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# Backlog Before Work

When you identify that work will need multiple steps or jobs: create backlog items for them — don't just describe them.

1. **Create or match a backlog item** — Use `create-backlog-item` or `work-backlog-item` before starting.
2. **Plan** — When writing a plan, add it to the item via `mcp__plugin_dh_backlog__backlog_update(selector="{title}", plan="{path}")`.
3. **Progress** — When completing actions, update the task/plan artifact so progression is visible.

Skip only for trivial single-step requests (typos, one-off questions, immediate one-action fixes).

---
> Source: [Jamie-BitFlight/claude_skills](https://github.com/Jamie-BitFlight/claude_skills) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-06-16 -->
