# blade-ink-rs

> - This is a Rust workspace with `runtime`, `compiler`, `rinklecate`, and `conformance-tests`; use the toolchain pinned in `rust-toolchain.toml`.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/blade-ink-rs/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Repository Guidelines

- This is a Rust workspace with `runtime`, `compiler`, `rinklecate`, and `conformance-tests`; use the toolchain pinned in `rust-toolchain.toml`.
- Keep changes scoped and add or update focused tests when behavior changes. CI runs `cargo test` and `cargo test -p bladeink --features stream-json-parser`.
- After every task, run `cargo fmt --all` and `cargo clippy --workspace --all-targets --all-features -- -D warnings`. Do not consider the task complete until both pass.

---
> Source: [bladecoder/blade-ink-rs](https://github.com/bladecoder/blade-ink-rs) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-06-29 -->
