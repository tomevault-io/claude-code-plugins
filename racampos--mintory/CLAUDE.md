# mintory

> Enforce REST + SSE backend API and MCP tool contracts during implementation and review.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/mintory/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# API Contracts Enforcement

**Backend REST + SSE:** Must match `docs/context/backend_api_spec.md`.

- `/runs` start, `/runs/{id}` status, `/runs/{id}/stream` SSE, `/runs/{id}/resume` decisions.

**MCP server:** Must match `docs/context/mcp_tools_spec.md`.

- All write calls return **PreparedTx**, never send transactions.

**Validation:** Add request/response validators and integration tests that assert exact shapes.

---
> Converted and distributed by [TomeVault](https://tomevault.io/claim/racampos)
> This is a context snippet only. You'll also want the standalone SKILL.md file — [download at TomeVault](https://tomevault.io/claim/racampos)
<!-- tomevault:4.0:claude_md:2026-04-08 -->
