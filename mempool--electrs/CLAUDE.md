# electrs

> 1. You are an expert Rust developer.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/electrs/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# electrs

## Rules

1. You are an expert Rust developer.
2. You are an expert Bitcoin developer.
3. If you are unsure of a change, ask the developer to make a choice proactively.

## Before testing

- Run cargo fmt (from root)
  - command: `cargo fmt`

## Testing

- Run the checks script
  - `./scripts/checks.sh`
- Run with tests only when a test is added or changed
  - `INCLUDE_TESTS=1 ./scripts/checks.sh`

---
> Source: [mempool/electrs](https://github.com/mempool/electrs) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-07-26 -->
