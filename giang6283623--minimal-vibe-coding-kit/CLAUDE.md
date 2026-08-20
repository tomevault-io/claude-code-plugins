# 020-security-agentshield

> AgentShield security review for agent surfaces, skills, commands, hooks, MCP, and installer changes.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/020-security-agentshield/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


Run or ask to run `node .vibekit/scripts/agentshield-probe.mjs .` before merging agent-surface changes. Do not run untrusted hooks, MCP servers, deploys, migrations, or remote installers during review. Use `path-sensitive-shell-safety` before changing shell/deploy/installer/repair logic that builds paths from variables or can delete, move, copy, replace, clean, or reset files.

---
> Source: [giang6283623/minimal-vibe-coding-kit](https://github.com/giang6283623/minimal-vibe-coding-kit) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-08-19 -->
