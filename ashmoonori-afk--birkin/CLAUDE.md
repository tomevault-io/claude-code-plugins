# birkin

> Whenever the user asks to commit and push, all three gates are mandatory before

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/birkin/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Repository Agent Rules

## Commit and push gate

Whenever the user asks to commit and push, all three gates are mandatory before
staging the final change:

1. Run the relevant CLI tests and manually exercise the affected CLI surface,
   including `--help`, a successful command, and one invalid input.
2. Update and cross-check both `README.md` and `README.ko.md` against the
   behavior being published.
3. Review the changed trust boundaries, run the relevant security regression
   tests, and run an available static security scan.

Do not commit or push until every gate passes. Preserve unrelated user files and
report any unavailable check explicitly.

---
> Source: [ashmoonori-afk/birkin](https://github.com/ashmoonori-afk/birkin) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-08-13 -->
