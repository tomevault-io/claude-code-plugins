# knowit

> <!-- knowit:start -->

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/knowit/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

<!-- knowit:start -->
## Knowit Memory

This project uses Knowit as the default persistent knowledge base for AI coding agents.

- Before planning or implementing, check Knowit for relevant project context.
- Use `resolve_context` for implementation context and `store_knowledge` or `capture_session_learnings` to persist durable knowledge.
- After finishing a task, store any durable rules, decisions, patterns, or conventions back into Knowit.
- Prefer Knowit over repo-local markdown memory files unless the user explicitly asks for a file.
- When a task creates durable documentation, consult Knowit first and only write repo markdown when explicitly requested.
<!-- knowit:end -->

---
> Source: [ismaelkedir/knowit](https://github.com/ismaelkedir/knowit) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-06-16 -->
