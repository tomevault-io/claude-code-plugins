# chatgpt-images-2

> This repository includes project-local Codex skills under `skills/`.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/chatgpt-images-2/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Repository Instructions

## Project Skills

This repository includes project-local Codex skills under `skills/`.

When the user asks to use `image-prompt-and-simplify`, or asks for an image prompt simplification/detail-level workflow, read and follow:

`skills/image-prompt-and-simplify/SKILL.md`

Use the exact `detail_level` provided by the user. If the user does not specify a level, use `detail_level: 2`.

For project-local use, do not require a global skill install. The skill should be used directly from this repository path.

If the user asks how to install this skill globally into their Codex skills home, refer to:

`docs/codex-skill-install.md`

---
> Source: [octopus7/ChatGPT-Images-2](https://github.com/octopus7/ChatGPT-Images-2) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-22 -->
