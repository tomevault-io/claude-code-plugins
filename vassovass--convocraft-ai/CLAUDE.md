# convocraft-ai

> - id: docs-sync-agent

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/convocraft-ai/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

version: 1

rules:
  - id: docs-sync-agent
    name: Docs Sync Agent
    description: |
      Runs documentation linting when API files change to ensure README/docs stay updated.
    trigger: onFileChange(src/**/*.ts)
    run: node scripts/docsSync.js
    success_message: "✅ Docs in sync."
    failure_message: "❌ Documentation out of sync – please update docs."
 

---
> Converted and distributed by [TomeVault](https://tomevault.io/claim/vassovass)
> This is a context snippet only. You'll also want the standalone SKILL.md file — [download at TomeVault](https://tomevault.io/claim/vassovass)
<!-- tomevault:4.0:claude_md:2026-04-08 -->
