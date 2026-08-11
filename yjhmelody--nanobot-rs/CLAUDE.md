# nanobot-rs

> For any code change that is ready to commit, run these checks first:

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/nanobot-rs/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Copilot Repository Instructions

For any code change that is ready to commit, run these checks first:

```bash
just fmt-check
taplo lint
cargo clippy --all-targets --all-features -- -D warnings
```

Before `git push`, also run:

```bash
cargo test --all-targets --all-features
```

Do not bypass these checks unless explicitly requested by the user.

---
> Source: [yjhmelody/nanobot-rs](https://github.com/yjhmelody/nanobot-rs) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-08-11 -->
