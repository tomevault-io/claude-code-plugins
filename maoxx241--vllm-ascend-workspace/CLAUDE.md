# skill-maintenance

> Synchronization constraints when editing agent skill packages under .agents/skills/

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/skill-maintenance/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# Skill Package Maintenance

When modifying any skill package, follow the maintenance rule in `AGENTS.md` — keep the per-skill bundle (SKILL.md + scripts/ + references/), shared modules, and remote-code-parity files in sync.

## Script conventions (supplemental to AGENTS.md)

- CLI parsers must accept common aliases and disable brittle prefix-abbreviation.
- Progress on `stderr` (`__VAWS_PROGRESS__=<json>`), final payload on `stdout` (single JSON object).
- Default metadata that can be safely inferred; never silently default security-sensitive values.

---
> Source: [maoxx241/vllm-ascend-workspace](https://github.com/maoxx241/vllm-ascend-workspace) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-06-22 -->
