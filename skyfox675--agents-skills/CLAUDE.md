# agents-skills

> This repository's working instructions are maintained tool-neutrally in [`AGENTS.md`](../AGENTS.md) (Claude Code's copy is [`CLAUDE.md`](../CLAUDE.md)). Read `AGENTS.md` first — it is the source of truth. The essentials:

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/agents-skills/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# GitHub Copilot instructions

This repository's working instructions are maintained tool-neutrally in [`AGENTS.md`](../AGENTS.md) (Claude Code's copy is [`CLAUDE.md`](../CLAUDE.md)). Read `AGENTS.md` first — it is the source of truth. The essentials:

- **Public, shareable collection of AI toolchains** (Skills + Agents) consumed across Claude Code, Copilot, and Cursor. Content/config repo — no build, no tests; validate artifacts by structure.
- **No personal or prior-project data.** No employer names, internal URLs, ticket IDs, secrets, or private paths. Keep learnings generic and reusable.
- **A skill/agent `name` is a public API** — keep it stable; renaming breaks consumers. Pointer skills (thin `SKILL.md` → upstream) keep the local name even when the upstream target moves.
- **Models lean Anthropic** (Opus default; Sonnet/Haiku by effort). Substitute other providers only when context window and reasoning effort match; note the substitution.

---
> Source: [skyfox675/agents-skills](https://github.com/skyfox675/agents-skills) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-08-31 -->
