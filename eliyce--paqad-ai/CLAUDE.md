# paqad-ai

> Use this file as the repository entrypoint for GitHub Copilot.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/paqad-ai/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# GitHub Copilot Instructions

Use this file as the repository entrypoint for GitHub Copilot.

Before any repository work, open `.paqad/framework-path.txt`, resolve the reference inside it to the paqad install directory, and load and follow the framework bootstrap it points to (`AGENT-BOOTSTRAP.md` in that directory). That bootstrap decides — based on whether paqad is enabled — what to load and how to behave.

**Fallback:** if `.paqad/framework-path.txt` is missing or cannot be resolved, or paqad is disabled, proceed as a normal assistant with no paqad behavior. Do not block.

Adapter:
github-copilot

---
> Source: [Eliyce/paqad-ai](https://github.com/Eliyce/paqad-ai) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-08-04 -->
