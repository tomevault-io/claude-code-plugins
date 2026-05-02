# changelog

> Update CHANGELOG.md for user-visible changes (Keep a Changelog)

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/changelog/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# Changelog

When a change affects **users or operators** (API, CLI, behavior, docs readers care about, examples, defaults), add a bullet under **`## [Unreleased]`** in [CHANGELOG.md](CHANGELOG.md) in the right section: **Added**, **Changed**, **Deprecated**, **Removed**, **Fixed**, or **Security**.

Skip changelog entries for internal refactors, test-only changes, and CI/tooling that does not change user-visible behavior. Full policy: [CONTRIBUTING.md](CONTRIBUTING.md) (section **Changelog**).

If the PR already has a suitable `[Unreleased]` entry, do not duplicate; extend it.

---
> Source: [OrlojHQ/orloj](https://github.com/OrlojHQ/orloj) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-04-22 -->
