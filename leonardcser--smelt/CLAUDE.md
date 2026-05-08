# smelt

> cargo test --workspace

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/smelt/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

## Commands

```bash
# build
cargo build

# test
cargo test --workspace

# format and lint
cargo fmt && cargo clippy --workspace --all-targets -- -D warnings
```

Whenever you add a new user-facing feature or change user-facing behavior,
update the README.md and the docs/ folder. Don't document internal
implementation details — only things end users need to know.

---
> Source: [leonardcser/smelt](https://github.com/leonardcser/smelt) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-03 -->
