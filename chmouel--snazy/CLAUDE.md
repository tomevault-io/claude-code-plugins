# snazy

> Whenever you make a code change make sure you run the following commands:

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/snazy/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

Whenever you make a code change make sure you run the following commands:

```bash
cargo fmt
cargo clippy --all-targets --all-features -- -D warnings 
cargo test --all-features
```

---
> Source: [chmouel/snazy](https://github.com/chmouel/snazy) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-07-27 -->
