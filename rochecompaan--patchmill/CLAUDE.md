# patchmill

> - When updating any skill pack or skill-pack dependency, verify both sides of

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/patchmill/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Patchmill agent instructions

## Verification

- When updating any skill pack or skill-pack dependency, verify both sides of
  the integration:
  - installed upstream skill files exist at the paths Patchmill resolves; and
  - Patchmill skill-pack config, metadata, tests, and live dependency references
    point at the same upstream version.
- When npm dependencies change (`package.json`, `package-lock.json`, or
  `npm-shrinkwrap.json`), rerun the Nix build as part of verification.

---
> Source: [rochecompaan/patchmill](https://github.com/rochecompaan/patchmill) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-08-10 -->
