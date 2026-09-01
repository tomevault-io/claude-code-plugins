# ai-ux-upsilon

> When working on this codebase, follow these guidelines:

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/ai-ux-upsilon/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Agent Guidelines

When working on this codebase, follow these guidelines:

- Keep the existing architecture intact — do not redesign the UI or rewrite working systems
- Never hardcode API keys or secrets — always use environment variables
- The `.env` file must never be committed — use `.env.example` for templates
- Supabase integration is in `src/lib/supabase.ts` — all DB calls go through that file
- AI provider routing is in `src/server.ts` and `src/lib/gemini.ts`
- The main chat UI is in `src/routes/index.tsx`

---
> Source: [MrZoic/ai-ux-upsilon](https://github.com/MrZoic/ai-ux-upsilon) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-09-01 -->
