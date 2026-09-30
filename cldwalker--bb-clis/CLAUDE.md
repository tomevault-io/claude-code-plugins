# bb-clis

> All changes must pass:

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/bb-clis/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Instructions

## Checks required for all changes

All changes must pass:

- `clojure -M:clj-kondo --lint src test`
- `bb --config dev-bb.edn lint:large-vars`

## Additional checks for larger changes

For changes with more than 10 lines, the other two bb linters from `.github/workflows/test.yml` and the test suite must also pass:

- `bb --config dev-bb.edn lint:ns-docstrings`
- `bb --config dev-bb.edn lint:minimize-public-vars`
- `bb clj:test`

---
> Source: [cldwalker/bb-clis](https://github.com/cldwalker/bb-clis) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-09-30 -->
