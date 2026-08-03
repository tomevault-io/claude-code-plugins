# setup

> Public repository for installer scripts and GitHub Action setup.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/setup/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# AGENTS: setup

Public repository for installer scripts and GitHub Action setup.

## Core Commands

- `npm install`
- `npm run dist`
- `sh ./installer.sh --help`

## Always Do

- Keep installer behavior explicit across macOS, Linux, and Windows.
- Preserve action input/output contract stability.

## Ask First

- Any change to default install paths or update behavior.
- Any action permission or deployment behavior change.

## Never Do

- Never remove installer safety checks.
- Never introduce hidden network side effects without documentation.

---
> Source: [pkgxdev/setup](https://github.com/pkgxdev/setup) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-07-22 -->
