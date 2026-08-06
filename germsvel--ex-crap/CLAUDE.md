# ex-crap

> - This is an Elixir/Mix library and Mix task for CRAP scoring.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/ex-crap/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# AGENTS.md

- This is an Elixir/Mix library and Mix task for CRAP scoring.
- Use `mix precommit` as the main local quality gate before claiming work is ready.
- For focused changes, run the relevant test file with `mix test path/to_test.exs` first.
- Do not edit generated artifacts in `doc/`, `cover/`, or `tmp/` unless explicitly asked.
- Boundary snapshots are checked with `mix boundary.spec.check`.
- Never manually edit `priv/boundary_spec.txt`; boundary spec updates require
human approval through `mix boundary.spec.check` and `mix boundary.spec.accept`

---
> Source: [germsvel/ex_crap](https://github.com/germsvel/ex_crap) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-07-27 -->
