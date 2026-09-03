# rust-engine-ci

> >-

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/rust-engine-ci/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# Rust engine: format check (CI parity)

CI runs `cargo fmt --all -- --check` with working directory `engine/` (see `.github/workflows/ci.yml`).

Before you mark Rust work complete or commit:

1. `cd engine && cargo fmt --all -- --check`
2. If it fails: `cd engine && cargo fmt --all`, then re-run the check.

Optional: `pre-commit install` uses `.pre-commit-config.yaml` to run this on commit when `engine/**/*.rs` changes.

---
> Source: [aurintex/pai-os](https://github.com/aurintex/pai-os) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-09-03 -->
