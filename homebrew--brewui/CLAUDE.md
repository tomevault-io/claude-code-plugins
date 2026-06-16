# package-domain-reference

> Package domain model lookup identity.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/package-domain-reference/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# Package Domain Reference

- Any domain model that represents a Homebrew package must expose `id` typed as `HomebrewPackageID` for lookup identity.
- Use `.formula(name:)` for formula-backed models and `.cask(token:)` for cask-backed models.
- Prefer deriving `name`/display fields from `HomebrewPackageID.name` where practical to avoid duplicate identity sources.

---
> Source: [Homebrew/BrewUI](https://github.com/Homebrew/BrewUI) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-06-16 -->
