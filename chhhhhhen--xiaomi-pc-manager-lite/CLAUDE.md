# xiaomi-pc-manager-lite

> - Always best solution, do not simplify or do half when task is complicate.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/xiaomi-pc-manager-lite/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# opencode agent instructions

## Coding rules

- Always best solution, do not simplify or do half when task is complicate.
- Always keep high quality, no hack error/warning bypass, solve them directly.
- No unsafe allowed.

## build/lint commands

### Build
- `cargo build` — debug build
- `cargo build --release` — release build
- `cargo check` — type check only
- `cargo clippy` — lint
- `cargo fmt --check` — formatting check (keep the tree rustfmt-clean)

### Run
- `cargo run` — run from terminal
- The binary is at `target/debug/xiaomi-pc-manager-lite.exe`

All commands run from project root (`D:\VSCodeProjects\xiaomi_pc_manager_lite`).

### Full verify before commit
```
cargo check && cargo clippy
```

---
> Source: [CHHHHHHEN/xiaomi_pc_manager_lite](https://github.com/CHHHHHHEN/xiaomi_pc_manager_lite) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-09-02 -->
