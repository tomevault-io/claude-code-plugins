# donna

> This document provides instructions and guidelines for the AI agents working on this project.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/donna/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Instructions for the AI Agents

This document provides instructions and guidelines for the AI agents working on this project.

Every agent MUST follow the rules and guidelines outlined in this document when performing their work.

## Donna tool

Since this is the repository that contains the Donna project itself, you have direct access to the Donna CLI tool via `./bin/donna.sh` script. I.e. you develop Donna using Donna.

In all commands that use `donna`, you MUST replace `donna` with `./bin/donna.sh` when you run the command.

For example, instead of `donna artifacts view '*:intro'` you MUST run `./bin/donna.sh artifacts view '*:intro'`.

---
> Source: [Tiendil/donna](https://github.com/Tiendil/donna) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-03 -->
