# siomon

> Debian packaging templates for building source packages uploaded to a

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/siomon/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Launchpad PPA Packaging - Agent Context

## Purpose

Debian packaging templates for building source packages uploaded to a
Launchpad PPA. The files here are **templates** — the CI workflow copies
them into a build directory, then modifies them per Ubuntu series.

## Key Sources

- `packaging/launchpad/README.md` — how the build process works, version
  format, series-specific handling, and local testing instructions.
- `.github/workflows/publish-ppa.yml` — the workflow implementation.
- `.github/workflows/gpg-keyserver-retry.yml` — GPG key propagation retry
  loop (dispatched automatically when needed).
- `PACKAGING.md` — one-time setup guide for secrets, GPG keys, Launchpad
  account, and GitHub environment configuration.

---
> Source: [level1techs/siomon](https://github.com/level1techs/siomon) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-07-22 -->
