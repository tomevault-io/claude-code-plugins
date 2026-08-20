# open-terminal-k8s-proxy

> Always run linting and tests after finishing changes:

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/open-terminal-k8s-proxy/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Agent Instructions
Always run linting and tests after finishing changes:

- **Linting**: `ruff check .` and `mypy terminal_proxy`
- **Tests**: `pytest tests -v --tb=short`

## Pre-commit Checks

Always run linting and tests before committing changes:

- **Linting**: `ruff check .` and `mypy terminal_proxy`
- **Tests**: `pytest tests -v --tb=short`

## Pull Request Attributions

When a pull request is merged, add an entry to the attributions table in `README.md` before committing any follow-up changes.

Command to check for newly merged PRs:
```
git log --merges --format='%H %s' origin/main
```

---
> Source: [volkermauel/open-terminal-k8s-proxy](https://github.com/volkermauel/open-terminal-k8s-proxy) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-08-20 -->
