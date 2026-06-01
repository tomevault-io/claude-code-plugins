# koota

> This monorepo uses `pnpm`.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/koota/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

This monorepo uses `pnpm`.

**IMPORTANT:** Always use kebab-case for file names, even if it is not the usual convention.

The `skills/koota` directory contains a skill with reference documentation for the koota project. When updating the README, the skill should be updated as well to keep documentation in sync. Follow best practices for agent skills.

## Benchmarks

Benchmarks live in `benches/`. Benches should be run only for the relevant set using the tags or names and then compared to look for regressions or to optimize code.

```sh
# Run suites using tags or by name and name with -n
pnpm bench "@relation @graph" -n "Name"

# Set baseline
pnpm bench baseline "Name"

# Compare baseline to a test by name
pnpm bench compare "Name"
```

---
> Source: [pmndrs/koota](https://github.com/pmndrs/koota) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-06-01 -->
