# syncthrough

> - Default branch is `master`, not `main`. When creating PRs or choosing a base branch, target `master` unless the user says otherwise.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/syncthrough/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# AGENTS.md

## Workflow constraints
- Default branch is `master`, not `main`. When creating PRs or choosing a base branch, target `master` unless the user says otherwise.
- Use feature branches and pull requests for changes; do not push directly to `master`.

## Task-specific constraints
- If you change public behavior, examples, or the documented API, update `README.md` in the same change.
- When editing docs that add or change external links, verify the new URLs return HTTP 200 before finishing.

---
> Source: [mcollina/syncthrough](https://github.com/mcollina/syncthrough) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-07-20 -->
