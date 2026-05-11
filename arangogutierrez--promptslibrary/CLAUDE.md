# rust

> Rust standards

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/rust/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Rust
style:clippy-clean|rustfmt|no-unsafe-unless-justified
pattern:Result>panic|enum-for-state-machines|newtype-for-validation
error:thiserror-for-library|anyhow-for-application|?-propagation
lifetime:minimize-annotations|owned-in-API|borrow-internally
test:cargo-test|#[cfg(test)]|proptest-for-invariants
security:no-unwrap-in-production|audit-deps(cargo-audit)|no-unsafe-ffi-leaks

---
> Source: [ArangoGutierrez/promptsLibrary](https://github.com/ArangoGutierrez/promptsLibrary) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-08 -->
