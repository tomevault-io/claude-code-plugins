# project-guidelines-rules

> Document architectural decisions, naming conventions, and structure to keep the team aligned.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/project-guidelines-rules/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Rule: Auto-generate and maintain PROJECT_GUIDELINES.md

Purpose:
Document architectural decisions, naming conventions, and structure to keep the team aligned.

When to run:
- When new packages/apps are added to the monorepo
- When naming, structure, or styling conventions change
- When deployment or integration workflows are updated

Include:
- Tech stack overview (frontend, backend, DB)
- Folder structure and purpose (`apps/`, `packages/`)
- Naming conventions for files, types, and functions
- Component standards (hooks only, styled-components usage)
- Deployment strategy (Vercel, AWS, preview vs prod)

Format:
Clean markdown with collapsible sections or bullet points for quick reference.

---
> Source: [drumnation/unsplash-smart-mcp-server](https://github.com/drumnation/unsplash-smart-mcp-server) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-19 -->
