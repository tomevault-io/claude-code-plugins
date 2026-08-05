# agent-proxy

> Read and follow `AGENTS.md`, `SPEC.md`, `ROADMAP.md`, and `TASKS.md` before

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/agent-proxy/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Copilot repository instructions

Read and follow `AGENTS.md`, `SPEC.md`, `ROADMAP.md`, and `TASKS.md` before
changing this repository.

The product is a per-login-user localhost gateway. Every inference request
routed to a built-in CLI must create or reuse a Herdr-managed agent owned by
the current user. Do not reintroduce a dedicated service account, root-owned
runtime paths, or an invisible headless provider fallback.

Keep changes aligned with the active Phase 4 tasks and run the validation gate
documented in `AGENTS.md`.

---
> Source: [ChrisTitusTech/agent-proxy](https://github.com/ChrisTitusTech/agent-proxy) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-08-05 -->
