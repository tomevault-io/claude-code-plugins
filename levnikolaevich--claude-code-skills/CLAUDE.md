# claude-code-skills

> <!-- Projection of AGENTS.md via the @ import. AGENTS.md is the canonical source. Do not duplicate content here — add it to AGENTS.md instead. -->

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/claude-code-skills/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# GEMINI.md

<!-- Projection of AGENTS.md via the @ import. AGENTS.md is the canonical source. Do not duplicate content here — add it to AGENTS.md instead. -->

@AGENTS.md

## Gemini CLI

- Context-compression preservation order: architecture decisions, modified files, verification status, open TODOs, tool outputs as summaries only.
- Run `/memory show` to inspect the resolved context (AGENTS.md + this file + any nested GEMINI.md files) and `/memory reload` after editing AGENTS.md.
- For modular context, use `@relative/path.md` imports in GEMINI.md itself — same 5-hop recursion limit as Claude Code.

---
> Source: [levnikolaevich/claude-code-skills](https://github.com/levnikolaevich/claude-code-skills) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-04-20 -->
