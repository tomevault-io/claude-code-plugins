# oomwrap

> - Use the Slophammer Rust standards from `osolmaz/slophammer/docs/AGENT_ENTRYPOINT.md`.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/oomwrap/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# AGENTS.md

- Use the Slophammer Rust standards from `osolmaz/slophammer/docs/AGENT_ENTRYPOINT.md`.
- Keep the guard core independent from CLI formatting, shell shim generation, and filesystem IO when practical.
- Do not add unsafe Rust unless there is no safe OS API for the operation and the reason is documented in code.
- Do not weaken memory guards or tests to make local checks pass.
- Run these commands before finishing code changes:

```bash
cargo fmt --check
cargo check --workspace
cargo clippy --workspace --all-targets -- -D warnings
cargo test --workspace --all-targets
```

Run `slophammer-rs check .` when `slophammer-rs` is available locally.

---
> Source: [osolmaz/oomwrap](https://github.com/osolmaz/oomwrap) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-09-19 -->
