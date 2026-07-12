# prof

> Entry point for coding agents in **prof** (Go profiling CLI). Navigate to the documentation file that best matches your task.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/prof/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Agent instructions

Entry point for coding agents in **prof** (Go profiling CLI). Navigate to the documentation file that best matches your task.


| Need | Doc |
| --- | --- |
| Package layout, call flow, invariants, `go test ./...` | [CODEBASE_DESIGN.md](CODEBASE_DESIGN.md) |
| Trace interactive collect internally (`prof tui` / `prof ui`) | [docs/collect-request-flow.md](docs/collect-request-flow.md) |
| Test layers, coverage, harness | [TESTING.md](TESTING.md) |
| PR workflow and contribution steps | [CONTRIBUTING.md](CONTRIBUTING.md) |
| Tool playbooks (Codegraph MCP, etc.) | [docs/agents/README.md](docs/agents/README.md) |
| Cursor behavioral rules | [.cursor/rules/](.cursor/rules/) |

---
> Source: [AlexsanderHamir/prof](https://github.com/AlexsanderHamir/prof) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-07-12 -->
