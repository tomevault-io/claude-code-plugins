# rust-template

> AI agents working on this Rust project must follow these guidelines.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/rust-template/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Development Instructions

AI agents working on this Rust project must follow these guidelines.

References:

- **Project overview**: @README.md
- **Dependencies**: @Cargo.toml

## Validation

After changing Rust code, run these commands in order:

1. `just full-check` — verify formatting and run Clippy with warnings denied.
2. `just test` — run the test suite.

If the formatting check fails, run `just full-write`, then rerun the validation commands. Run `just --list` to see the
available recipes.

---
> Source: [PaulRBerg/rust-template](https://github.com/PaulRBerg/rust-template) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-09-08 -->
