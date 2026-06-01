# code-formatters

> These tools modify code automatically. Run them before finalizing changes so the codebase stays consistent.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/code-formatters/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# Code formatters & refactors (auto-updating tools)

These tools modify code automatically. Run them before finalizing changes so the codebase stays consistent.

## Rector

- Run `vendor/bin/rector --ansi` before finalizing changes so refactoring rules are applied.
- Rector updates code on its own; run it to keep the codebase aligned with configured rules.

---
> Source: [CodeWithDennis/larament](https://github.com/CodeWithDennis/larament) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-06-01 -->
