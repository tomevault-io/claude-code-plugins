# pkgx

> Public core CLI repository for running packages.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/pkgx/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# AGENTS: pkgx

Public core CLI repository for running packages.

## Core Commands

- `cargo fmt --all -- --check`
- `cargo clippy --all-features`
- `cargo test --all-features`

## Always Do

- Preserve CLI semantics and user-facing flags unless intentionally versioned.
- Keep changes in `crates/lib` and `crates/cli` compatibility-aware.
- Add tests for changed runtime behavior.

## Ask First

- Breaking CLI behavior changes.
- Distribution/release workflow changes.

## Never Do

- Never skip tests on core execution path changes.
- Never merge compatibility-sensitive changes without impact notes.

---
> Source: [pkgxdev/pkgx](https://github.com/pkgxdev/pkgx) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-07-20 -->
