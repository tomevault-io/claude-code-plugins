# ai-science-toolkit

> This repository is shared between Codex and Claude Code.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/ai-science-toolkit/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# AGENTS.md

This repository is shared between Codex and Claude Code.

## Shared Guidance

Use `CLAUDE.md` as the source of truth for durable repository context, workflow notes, and skill-development conventions. Codex should read and follow the applicable project guidance there unless it conflicts with higher-priority Codex instructions.

## Agent-Specific Notes

- Claude Code uses `CLAUDE.md` and `.claude/`.
- Codex uses this `AGENTS.md` entry point and `.codex/`.
- Keep shared repository knowledge in `CLAUDE.md` unless it is genuinely specific to one agent.
- Keep local/session state in `.ai/` when using the existing handoff workflow.

## Editing Rule

For Claude skills, edit the repo copy under `skills/`, then sync with `scripts/sync.sh`. Do not edit installed copies directly.

---
> Source: [dgilford/ai-science-toolkit](https://github.com/dgilford/ai-science-toolkit) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-07-29 -->
