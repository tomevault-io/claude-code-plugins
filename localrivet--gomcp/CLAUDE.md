# be-very-stingy-with-locks

> When writing golang be very stingy and sparing with mutex locks. locks ofter produce more problems than not. where possible use atomics and avoid locks.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/be-very-stingy-with-locks/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

When writing golang be very stingy and sparing with mutex locks. locks ofter produce more problems than not. where possible use atomics and avoid locks.

Locks are hard to debug because child process could be trying to get a lock or release a lock of a parent lock.

it's better to avoid them with better designs.

---
> Source: [localrivet/gomcp](https://github.com/localrivet/gomcp) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-19 -->
