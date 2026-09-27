# oximux

> Pointers only (no duplicated content — these files are the source of truth):

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/oximux/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Agent guide — OxiMux

Pointers only (no duplicated content — these files are the source of truth):

- **Start here:** [`README.md`](README.md) — stack, repo layout, capabilities, working agreements.
- **Where things live:** [`docs/system-architecture.md`](docs/system-architecture.md) → **"Source map — where things live"** — crate + `shell/<domain>/` index for fast navigation.
- **Design contract:** [`docs/design-guidelines.md`](docs/design-guidelines.md) — palette, density, typography.
- **File-size policy:** lint enforces warn > 1500 / fail > 3000 non-blank LOC + a ratchet allowlist (`xtask/file-size-allow.txt`); aim for < 500 LOC per file. Never run `cargo fmt` (repo is not fmt-clean).

---
> Source: [nhtera/OxiMux](https://github.com/nhtera/OxiMux) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-09-23 -->
