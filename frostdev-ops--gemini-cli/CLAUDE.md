# coding-style

> This project follows standard Rust coding conventions.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/coding-style/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Coding Style Guidelines

This project follows standard Rust coding conventions.

## Formatting

*   Code formatting is enforced using `rustfmt`. Ensure `rustfmt` is run before committing changes.
*   Configuration for `rustfmt` might be present in `rustfmt.toml` or within [`Cargo.toml`](mdc:Cargo.toml) files (though none was found in the root `Cargo.toml`). Assume default settings if no explicit configuration is found.

## Linting

*   Code linting is performed using `clippy`.
*   Run `cargo clippy` regularly to catch potential issues and improve code quality.
*   Clippy configuration (e.g., allowed lints) might be present in `clippy.toml` or via attributes in the source code.

## General Conventions

*   Follow the guidelines outlined in the official [Rust API Guidelines](mdc:https:/rust-lang.github.io/api-guidelines).
*   Use descriptive names for variables, functions, structs, enums, and traits.
*   Write documentation comments for public APIs.

---
> Source: [frostdev-ops/gemini-cli](https://github.com/frostdev-ops/gemini-cli) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-20 -->
