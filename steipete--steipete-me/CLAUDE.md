# steipete-me

> - If user says “new blog post” without topic/title: ask for topic/title first.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/steipete-me/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# AGENTS.md
## New Blog Post Workflow
- If user says “new blog post” without topic/title: ask for topic/title first.
- Pick branch name: short slug from topic/title.
- Scaffold file: `src/content/blog/<year>/<slug>.md`.
- Frontmatter: only set `title` from user input; keep required placeholders minimal (`description: "TBD"`, `draft: true`, `pubDatetime: <today>`).
- No body content; no invented outline.
- Open editor: `code <new-post-path>`.

---
> Source: [steipete/steipete.me](https://github.com/steipete/steipete.me) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-17 -->
