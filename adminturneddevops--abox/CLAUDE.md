# abox

> - Host processes never execute model-authored commands.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/abox/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# ABox contributor rules

- Host processes never execute model-authored commands.
- Guest packages must not import `internal/tui`, `internal/provider`, or `cmd/abox`.
- Isolation claims stay Planned until Phase 0.5/18 hardware tests pass.
- Do not add host filesystem mounts, guest NICs, or TSI.
- Tests must not contain secrets.
- Five built-in tools plus discovered MCP tools. No `write_file` in milestone one.

---
> Source: [AdminTurnedDevOps/ABox](https://github.com/AdminTurnedDevOps/ABox) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-08-22 -->
