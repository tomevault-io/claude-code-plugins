# response-conciseness

> description: Keep final responses concise by default

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/response-conciseness/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

---
description: Keep final responses concise by default
alwaysApply: true
---

# Response Conciseness

Default to concise final explanations to reduce token usage.

- Keep final answers short and task-focused.
- Include only the information needed to act on the result.
- Expand details only when the user explicitly asks for a deep explanation, walkthrough, or full rationale.
- For code changes, provide a brief outcome + key files changed; avoid long narrative unless requested.
- Prefer compact bullets over long paragraphs when listing results.

---
> Source: [sitar93/krono](https://github.com/sitar93/krono) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-22 -->
