# openclaw-studio

> Keep repository instructions generic and safe for open source.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/openclaw-studio/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Agent Instructions

Keep repository instructions generic and safe for open source.

This repo is a frontend for OpenClaw. The OpenClaw source code lives at ~/openclaw.

Do not modify the OpenClaw source code. When the user asks for changes, they are asking for changes to OpenClaw Studio (this app). Your solutions should be applied to this app but to understand the full context of implementing your solution, you will need to search through OpenClaw's source code. 

If present, also load local private overlay instructions from:
`$HOME/.codex/agents/openclaw-studio.local.md`

Do not commit personal, environment-specific, or secret instructions to this repository.

---
> Source: [grp06/openclaw-studio](https://github.com/grp06/openclaw-studio) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-04-20 -->
