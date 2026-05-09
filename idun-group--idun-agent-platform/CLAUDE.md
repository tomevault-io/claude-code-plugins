# engine

> Rules for working on the idun_agent_engine SDK

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/engine/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Idun Agent Engine

Read `libs/idun_agent_engine/CLAUDE.md` before making changes. It contains the full module map, config flow, agent adapter details, and conventions.

- All agent operations are async (`initialize`, `invoke`, `stream`).
- LangGraph expects an **uncompiled StateGraph** — the engine compiles it with checkpointer/store.
- Observability config is top-level, not inside `agent.config` (agent-level is deprecated).
- Dynamic imports for agent loading: file path first, Python module fallback.
- Schema models come from `idun_agent_schema` — don't duplicate them here.

---
> Source: [Idun-Group/idun-agent-platform](https://github.com/Idun-Group/idun-agent-platform) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-04 -->
