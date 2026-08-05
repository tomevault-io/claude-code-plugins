# pi-claude-bridge

> Do **not** auto-commit.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/pi-claude-bridge/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Agent Guidelines

## Commit

Do **not** auto-commit.

## Changelog

Maintain an entry in the `## UNRELEASED` section at the top of `CHANGELOG.md` for every significant change, using the existing format:

```
- **Tag: summary** — detail
```

Do not add changelog entries for docs-only changes. If multiple entries in the UNRELEASED section pertain to the same feature, try to combine them into one entry,

Tags: `Add`, `Fix`, `Refactor`, `Tests`, `Bump`, `Deprecate`, `Remove`.

## Tests

Smoke tests typically need to run outside a sandbox because they access local pi/Claude settings and auth state.

---
> Source: [elidickinson/pi-claude-bridge](https://github.com/elidickinson/pi-claude-bridge) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-07-25 -->
