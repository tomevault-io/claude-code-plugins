# htmlhint

> <!-- https://agents.md -->

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/htmlhint/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Agents

<!-- https://agents.md -->

## GitHub Actions

- The GitHub Actions workflows should be placed in the .github/workflows directory.
- The workflows should be named `<workflow-name>.yml`.
- All GitHub Actions should be pinned versions to avoid breaking changes (SHA-1).
- If using actions/checkout, it should have `persist-credentials: false` set.

## Dependabot

- GitHub Actions updates should be grouped and updated monthly.
- npm packages should be grouped and updated monthly.
- Dependabot config should be formatted with Prettier.

---
> Source: [htmlhint/HTMLHint](https://github.com/htmlhint/HTMLHint) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-07-21 -->
