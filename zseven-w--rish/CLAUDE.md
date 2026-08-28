# rish

> `rish` is a Rust workspace for a cross-platform Linux command and container

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/rish/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Repository instructions

`rish` is a Rust workspace for a cross-platform Linux command and container
semantic runtime.

## Design rules

- Never report semantic emulation as native kernel support.
- Every privileged operation must pass capability negotiation before dispatch.
- Platform code communicates with Rust through versioned JSON envelopes.
- Keep the portable core free of platform SDK dependencies.
- Unknown ELF executables must fail closed or route to an explicitly available
  native-Linux/VM backend.
- Keep source files below 800 lines.

## Validation

Run these from the repository root:

```bash
cargo fmt --check
cargo clippy --workspace --all-targets -- -D warnings
cargo test --workspace
```

---
> Source: [ZSeven-W/rish](https://github.com/ZSeven-W/rish) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-08-28 -->
