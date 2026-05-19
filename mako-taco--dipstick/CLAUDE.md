# dipstick

> When creating unit tests that require ts-morph structures, do not mock them.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/dipstick/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Unit testing
When creating unit tests that require ts-morph structures, do not mock them.
Instead, create a `__fixtures__` directory in the same directory as the test,
and add `.ts` source files to it, which can then be parsed by ts-morph.

---
> Source: [mako-taco/dipstick](https://github.com/mako-taco/dipstick) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-19 -->
