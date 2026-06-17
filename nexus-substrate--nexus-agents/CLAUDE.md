# nexus-agents

> This repo follows the [AGENTS.md](./AGENTS.md) federation (#2764 / #3446): **AGENTS.md is the single source of truth** for project conventions, rules, and agent guidance. It's the canonical, harness-neutral superset; harness-specific entry points redirect to it rather than duplicating content.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/nexus-agents/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Federated to AGENTS.md

This repo follows the [AGENTS.md](./AGENTS.md) federation (#2764 / #3446): **AGENTS.md is the single source of truth** for project conventions, rules, and agent guidance. It's the canonical, harness-neutral superset; harness-specific entry points redirect to it rather than duplicating content.

**For the Gemini CLI:** load [AGENTS.md](./AGENTS.md) as the project context. You can also point Gemini at it directly by setting `context.fileName` to `AGENTS.md` in your Gemini settings, instead of relying on this redirect. Keyword-scoped per-topic rules live in [`.rules/`](./.rules/) and are indexed from AGENTS.md.

See [docs/architecture/AGENT_COMPATIBILITY.md](./docs/architecture/AGENT_COMPATIBILITY.md) for the federation rationale and the per-harness compatibility matrix. (Claude Code's `CLAUDE.md` is generated from AGENTS.md's agnostic body plus a Claude-specific overlay — see `scripts/inject-governance.ts`.)

---
> Source: [nexus-substrate/nexus-agents](https://github.com/nexus-substrate/nexus-agents) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-06-17 -->
