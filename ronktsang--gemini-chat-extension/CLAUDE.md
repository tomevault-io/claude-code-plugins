# coding-style

> - **Naming**: Use descriptive names; avoid abbreviations; functions are verbs; variables are nouns

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/coding-style/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Coding Style (TypeScript/React)

- **Naming**: Use descriptive names; avoid abbreviations; functions are verbs; variables are nouns
- **Types**: Annotate exported/public APIs; avoid `any` and unsafe casts
- **Control Flow**: Prefer guard clauses and shallow nesting; avoid unnecessary try/catch and swallow-only handlers
- **Comments**: Only for non-obvious rationale, invariants, or caveats; keep concise; **always write comments in English**
- **Formatting**: Match existing style; wrap long lines; do not reformat unrelated code
- **Imports**: Keep paths aligned with existing alias usage (e.g., `@/utils/...`)
- **UI**: Prefer composition over prop drilling; colocate small helpers near usage

---
> Source: [RonkTsang/gemini-chat-extension](https://github.com/RonkTsang/gemini-chat-extension) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-06 -->
