# fission

> For decompiler-quality work, follow [`SKILL.md`](SKILL.md) first.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/fission/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Fission Gemini Instructions

For decompiler-quality work, follow [`SKILL.md`](SKILL.md) first.

Key constraints:

- Treat benchmark rows, Ghidra diffs, and AI suggestions as evidence only.
- Translate every semantic fix into an owner-native invariant before editing.
- Prefer shared CFG, def-use, type-constraint, calling-convention, or alias facts
  over another narrow pass.
- Do not add function/address/binary/corpus-specific production branches.
- Do not copy or depend on `vendor/` reference code.

---
> Source: [fission-systems/Fission](https://github.com/fission-systems/Fission) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-09-30 -->
