# chef-mate

> This project shares its agent instructions between Codex and Claude.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/chef-mate/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# AGENTS.md

This project shares its agent instructions between Codex and Claude.

Before working in this repository, read and follow:

- `.agents/seed.md` - shared project context, architecture, commands, testing, and git workflow.
- `.agents/skills/` - shared task playbooks. Use a skill when the user names it or the task clearly matches it.

The shared seed overrides any older or task-specific instruction that suggests pushing, opening a PR, or using a destructive command without an explicit current-message request from the user.

---
> Source: [Plus-Mobile-Apps/chef-mate](https://github.com/Plus-Mobile-Apps/chef-mate) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-08-13 -->
