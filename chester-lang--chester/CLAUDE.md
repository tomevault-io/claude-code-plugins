# chester

> - Chester language rule: `()` is value-only.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/chester/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Agent Rules

- Chester language rule: `()` is value-only.
- Chester language rule: `Unit` is type-only.
- In Chester code, if anything uses `()` in a type position, or otherwise misaligns with this design, that code is wrong and must be corrected.
- Note (Chester semantics): Types are first-class. `Unit` may appear in contexts that look value-like when it is being used as a type-level value.

---
> Source: [chester-lang/chester](https://github.com/chester-lang/chester) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-06-12 -->
