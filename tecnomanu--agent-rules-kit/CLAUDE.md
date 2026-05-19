# 01-coding-standards

> These apply to **all code** in this repository (TypeScript, PHP, Markdown, JSON):

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/01-coding-standards/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Global Coding Standards

These apply to **all code** in this repository (TypeScript, PHP, Markdown, JSON):

* Use **ESLint + Prettier** for all JavaScript/TypeScript files; run `npm run lint` before committing.
* PHP code must pass **PHP‑Stan level 8** and **Pint** auto‑format (run `composer pint`).
* Markdown follows the GitHub Markdown style guide; wrap lines at 120 chars.
* JSON files must be pretty‑printed with 2‑space indent.

> Any new template file must follow the same style conventions.

---
> Source: [tecnomanu/agent-rules-kit](https://github.com/tecnomanu/agent-rules-kit) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-18 -->
