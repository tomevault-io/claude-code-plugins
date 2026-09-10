# pal

> Persist pal CLI architectural decisions into project rules

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/pal/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Document pal CLI decisions

When the user makes an **architectural decision about the pal CLI** (`cmd/pal`) in a conversation — layout, frameworks, interactive vs non-interactive patterns, step/flag registries, Action/runner boundaries, exit-code conventions, naming, or similar — **update** [`.cursor/rules/pal-cli.mdc`](.cursor/rules/pal-cli.mdc) in the same turn (or before finishing the task).

- Write the decision as a concise, actionable convention (same style as existing CLI rules).
- Do not leave CLI architecture only in chat history.
- Do not edit the plan files for this; the CLI rule file is the source of truth for agents.
- If the decision revises an older rule, replace or amend the outdated text — keep the file coherent.

---
> Source: [zhulik/pal](https://github.com/zhulik/pal) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-09-10 -->
