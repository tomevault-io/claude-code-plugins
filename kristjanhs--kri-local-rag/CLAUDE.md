# kri-local-rag

> - never remove production docker volumes: This means never use -v when running on non-test containers:

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/kri-local-rag/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Gemini Guidelines

- never remove production docker volumes: This means never use -v when running on non-test containers:
  docker -f docker/docker-compose.yml compose down -v
- after each major code change, run linters to check if some lint errors need manual fixing:
 ruff check . --fix 
 pyright

---
> Converted and distributed by [TomeVault](https://tomevault.io/claim/KristjanHS)
> This is a context snippet only. You'll also want the standalone SKILL.md file — [download at TomeVault](https://tomevault.io/claim/KristjanHS)
<!-- tomevault:4.0:claude_md:2026-04-08 -->
