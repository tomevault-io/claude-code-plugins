# obsidian-ics

> When working on an issue and currently on the master branch, always create a new feature branch first.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/obsidian-ics/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Branch Management Rule
When working on an issue and currently on the master branch, always create a new feature branch first.

Use the format: `git checkout -b issue-{issue-number}` or `git checkout -b feature-{description}`

Since we use github, also publish the branch to `origin` (github)

This helps maintain a clean master branch and enables proper pull request workflows.

---
> Source: [open-horizon-labs/obsidian-ics](https://github.com/open-horizon-labs/obsidian-ics) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-07-24 -->
