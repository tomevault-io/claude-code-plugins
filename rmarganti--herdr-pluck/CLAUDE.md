# herdr-pluck

> - Add SUCCINCT docblocks to structs and methods.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/herdr-pluck/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

## Code documentation

- Add SUCCINCT docblocks to structs and methods.
- Give an added focus to Domain definitions.
- Do NOT document things that are painfully obvious. For example, a `Rect { w: int64, h: int64 }` has no need for documentation.
- If an implication is particularly complicated, document implementation sections.

## Verifying (MUST BE RUN BEFORE CONSIDERING A TASK COMPLETE)

- `cargo fmt --all -- --check`
- `cargo test --all-features`
- `cargo clippy --all-targets --all`
- Any live, end-to-end testing can be done with the `herdr` CLI and `/herdr` agent skill.

---
> Source: [rmarganti/herdr-pluck](https://github.com/rmarganti/herdr-pluck) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-08-14 -->
