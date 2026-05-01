# project

> Project-wide coding guidelines

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/project/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


This project uses PROJECT.md as the single source of truth for all AI agent instructions.
Read PROJECT.md in the project root for complete guidelines including tech stack, code conventions, and project structure.

Key points:
- Next.js 16 with App Router, React 19, TypeScript strict
- Tailwind CSS v4 with oklch tokens, shadcn/ui components
- Use cn() from @/lib/utils for class merging
- Named exports, PascalCase components, camelCase functions
- Mobile-first responsive design
- No `any` types, no inline styles

---
> Source: [CloveSVG/One-Click-Clone](https://github.com/CloveSVG/One-Click-Clone) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-04-20 -->
