# reipa

> Use **ripgrep (`rg`)**, not `grep`, for searching this repository.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/reipa/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Agent conventions

## Searching the codebase

Use **ripgrep (`rg`)**, not `grep`, for searching this repository.

`rg` respects `.gitignore` (so it skips `target/`, build artifacts, and the
large binaries under `scratchpad/`), is much faster on this tree, and has
saner defaults. Reach for it in scripts, ad-hoc searches, and CI.

- Search: `rg pattern` (recursive by default) instead of `grep -rn pattern .`
- Filter by type: `rg -t rust pattern` / `--glob '*.rs'`
- If a script must run where `rg` may be absent, install it or gate on
  `command -v rg` before falling back — do not default to `grep`.

---
> Source: [JRBusiness/REipa](https://github.com/JRBusiness/REipa) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-09-12 -->
