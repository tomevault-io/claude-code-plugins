# rust-formatting-rules

> rules for formatting rust code

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/rust-formatting-rules/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Rust Macros

When using `format!` or `assert!` macros in Rust, always put variables inside brackets when possible.
*Example*:

Instead of this:
`format!("Failed to fetch PUT result for {}", filename)`
Do this:
`format!("Failed to fetch PUT result for {filename}")`

---
> Source: [snowflakedb/universal-driver](https://github.com/snowflakedb/universal-driver) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-14 -->
