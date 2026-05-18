# grease

> GREASE is a Haskell library and command-line tool for under-constrained symbolic

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/grease/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# AGENTS.md

GREASE is a Haskell library and command-line tool for under-constrained symbolic
execution of binaries.

## Haskell

Format, build, and lint after every change.

- Format: `make -j8 -f scripts/lint/Makefile fmt`
- Build: `cabal build pkg:grease-exe`
- Lint: `make -j8 -f scripts/lint/Makefile hs`
- Test: `cd grease-exe && cabal run test:grease-tests`

### Error handling

Read error handling documentation at `doc/dev/errors.md`.

### Writing tests

See `doc/dev/tests.md`.

## `.cbl` files

Read docs at `doc/sexp.md` and `doc/sexp-progs.md`.

## `*shape*.txt` files

Read docs at `doc/shape-dsl.md`.

---
> Source: [GaloisInc/grease](https://github.com/GaloisInc/grease) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-18 -->
