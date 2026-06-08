# pr-workflow

> PR and CI workflow

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/pr-workflow/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# PR Workflow

When pushing or preparing to push, check that CI/CD has passed for the PR using:

```bash
gh pr checks 494   # or the relevant PR number
```

Run the equivalent for the correct PR before considering the push complete.

---
> Source: [goldsky-io/streamling](https://github.com/goldsky-io/streamling) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-06-08 -->
