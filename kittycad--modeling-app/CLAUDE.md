# modeling-app

> This file applies to all work in this repository. More-specific `AGENTS.md` files supplement it with guidance for their directories.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/modeling-app/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# AGENTS.md (Repository)

## Scope

This file applies to all work in this repository. More-specific `AGENTS.md` files supplement it with guidance for their directories.

## Pull requests

- Keep PR descriptions focused on information useful to reviewers: what changed, why, risks, and any non-obvious behavior or testing context. Do not add boilerplate validation sections listing routine tests, lints, or formatters; CI already reports those. Mention validation only when it adds specific, reviewer-relevant information.
- Open agent-created PRs as drafts and leave them in draft until the human who requested the work has self-reviewed them and marked them ready. At minimum, CI should be passing before the PR leaves draft.
- Do not modify CI configuration merely to make a feature or fix PR pass. Fix the implementation or tests instead. If the CI configuration itself is wrong, raise a separate issue and address it in a separate PR.

---
> Source: [KittyCAD/modeling-app](https://github.com/KittyCAD/modeling-app) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-09-08 -->
