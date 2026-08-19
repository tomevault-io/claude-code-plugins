# mcp-state-twin

> - Treat `docs/RFC-0001.md` and accepted ADRs as design authority.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/mcp-state-twin/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Repository instructions

- Treat `docs/RFC-0001.md` and accepted ADRs as design authority.
- Never describe roadmap items as implemented without executable tests.
- Do not add upstream passthrough or production-write paths to hermetic mode.
- Do not expose snapshot, fork, reset, state inspection, or fault controls as
  agent-facing MCP tools.
- Keep TwinSpec expressions declarative and resource-bounded; arbitrary script
  execution is out of scope.
- Unknown behavior must fail explicitly rather than return invented success.
- Run `gofmt`, `go vet ./...`, and `go test -race ./...` for code changes.
- Never commit real credentials, production traces, or personal data.

---
> Source: [augety121/MCP-State-Twin](https://github.com/augety121/MCP-State-Twin) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-08-19 -->
