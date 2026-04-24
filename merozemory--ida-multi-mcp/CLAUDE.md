# ida-multi-mcp

> Last updated: 2026-02-17

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/ida-multi-mcp/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# AGENTS

Last updated: 2026-02-17

## 1) Entry Rules
- Read order: `docs/README.md` -> `docs/.ssot/PRD.md` -> `docs/.ssot/contracts/*` -> target domain docs.
- Conflict resolution: Contracts are the source of truth.

## 2) Documentation Rules
- Do not redefine contract semantics outside `docs/.ssot/contracts/*`.
- Use links + versions when referencing contracts.
- Update absolute dates in modified docs.

## 3) Code/Docs Traceability
- When changing architecture or behavior docs, include references to affected code paths.
- Keep roadmap and PRD synchronized with repository reality.

## 4) Project Profile
- CLI-centric project
- No external HTTP API spec
- No DB-backed schema docs
- Uses AI agents
- Does not use RAG KB currently

---
> Source: [MeroZemory/ida-multi-mcp](https://github.com/MeroZemory/ida-multi-mcp) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-04-21 -->
