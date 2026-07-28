# jstime

> The canonical repository-wide agent guidance now lives in [`/AGENTS.md`](../AGENTS.md).

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/jstime/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# GitHub Copilot instructions for jstime

The canonical repository-wide agent guidance now lives in [`/AGENTS.md`](../AGENTS.md).

When GitHub Copilot works in this repository:

- treat `AGENTS.md` as the primary source of truth for project context and coding expectations
- keep changes minimal and aligned with existing Rust/V8 patterns
- run the appropriate validation commands before considering work complete:
  - `cargo fmt --all -- --check`
  - `cargo clippy --all-targets -- -D warnings`
  - `cargo test --locked`
- add or update tests when behavior changes
- update relevant docs when public APIs or developer workflows change

If this file and `AGENTS.md` ever diverge, follow `AGENTS.md` and update this shim.

---
> Source: [jstime/jstime](https://github.com/jstime/jstime) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-07-24 -->
