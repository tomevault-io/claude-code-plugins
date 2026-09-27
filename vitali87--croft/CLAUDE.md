# croft

> When reviewing pull requests:

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/croft/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Code review guidelines

When reviewing pull requests:

- Only leave comments for critical, major, or high-severity issues: logic
  bugs, security vulnerabilities, data loss or corruption, race conditions,
  and breaking API changes.
- Do NOT comment on code style, formatting, naming, comments/docstrings, or
  minor/optional refactoring suggestions — linters handle those.
- If no issue meets that bar, do not leave any inline comments.

---
> Source: [vitali87/croft](https://github.com/vitali87/croft) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-09-27 -->
