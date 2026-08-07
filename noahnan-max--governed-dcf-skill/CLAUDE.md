# governed-dcf-skill

> - Keep examples synthetic or user-provided.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/governed-dcf-skill/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Working agreement

- Keep examples synthetic or user-provided.
- Never invent missing financial facts; return `BLOCKED`.
- Keep valuation results separate from trade instructions.
- Preserve the public/private disclosure boundary in `SECURITY.md`.
- Run `python3 -m unittest discover -s tests -v` after calculation changes.
- Do not weaken `WACC > terminal growth`, probability, bridge, or finite-number checks.

---
> Source: [noahnan-max/governed-dcf-skill](https://github.com/noahnan-max/governed-dcf-skill) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-08-03 -->
