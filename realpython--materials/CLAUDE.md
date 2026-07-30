# materials

> This is a small command-line tool that reads a CSV of personal transactions and

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/materials/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Project conventions

This is a small command-line tool that reads a CSV of personal transactions and
prints a per-category expense summary.

## Money

- Represent every monetary amount with `decimal.Decimal`, never `float`.
- Quantize money to exactly two decimal places before displaying it.

## Style

- Keep functions small and single-purpose.
- Standard library only. No third-party dependencies.

---
> Source: [realpython/materials](https://github.com/realpython/materials) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-07-25 -->
