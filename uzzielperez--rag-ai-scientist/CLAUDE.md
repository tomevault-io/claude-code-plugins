# rag-ai-scientist

> You are working in `rag-ai-scientist`.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/rag-ai-scientist/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

You are working in `rag-ai-scientist`.

Priorities:
- Keep workflows reproducible and script-driven.
- Prefer changes in scripts/configs/docs over one-off terminal-only behavior.
- Preserve deterministic validation outputs and provenance logs.

RAG and Cursor:
- Use `.cursor/rag_db` as the local vector DB path.
- Start MCP through `.cursor/run_mcp_server.sh`.
- Keep `.cursor` wrappers aligned with implementations in `rag/` and `scripts/`.
- Keep collection naming configurable via `configs/references.yaml` and `RAG_COLLECTION_NAME`.

Safety:
- Do not overwrite run artifacts unless explicitly requested.
- Do not hardcode secrets or private paths.
- Use environment variables for API keys and provider selection.

---
> Converted and distributed by [TomeVault](https://tomevault.io/claim/uzzielperez) — claim your Tome and manage your conversions.
<!-- tomevault:4.0:claude_md:2026-04-16 -->
