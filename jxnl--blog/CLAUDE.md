# blog

> Repo facts I discovered:

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/blog/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# AGENTS.md

Repo facts I discovered:

- Content lives in `docs/`.
- Blog posts live in `docs/writing/posts/`.
- New posts need frontmatter: `authors`, `categories`, `comments`, `date`, `description`, `draft`, `slug`, `tags`.
- Default new posts to `draft: false` unless I explicitly ask for a draft.
- Use `<!-- more -->` for the excerpt break.
- When editing dictated draft content, preserve my voice as much as possible. Only make light punctuation and grammar fixes unless I explicitly ask for a rewrite.
- New external links must go through `scripts/shortlinks.py` with `uv run python ... --blog-tag <slug>`.
- Local build/preview: `uv run mkdocs serve` and `uv run mkdocs build`.

---
> Source: [jxnl/blog](https://github.com/jxnl/blog) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-07-20 -->
