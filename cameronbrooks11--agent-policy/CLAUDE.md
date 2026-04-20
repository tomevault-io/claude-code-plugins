# agent-policy

> agent-policy — Agent Policy Rules

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/agent-policy/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# agent-policy — Agent Policy

Schema-first generator for coding-agent repo policies and compatibility files.

## Commands

- Test: `cargo test`
- Lint: `cargo clippy --all-targets -- -D warnings`

## Edit permissions

You may freely edit:
- `src/**`
- `templates/**`
- `tests/**`
- `examples/**`

Do not modify without human review:
- `.github/workflows/**`
- `agent-policy.schema.json`
- `Cargo.toml`

## Constraints
- Never commit secrets or credentials.- Include tests with code changes.

---
> Converted and distributed by [TomeVault](https://tomevault.io/claim/CameronBrooks11) — claim your Tome and manage your conversions.
<!-- tomevault:4.0:claude_md:2026-04-13 -->
