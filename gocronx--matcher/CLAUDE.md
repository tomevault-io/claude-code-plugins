# matcher

> Conventions for AI coding assistants (Codex, Cursor, Copilot) and humans alike.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/matcher/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# AGENTS.md

Conventions for AI coding assistants (Codex, Cursor, Copilot) and humans alike.
Claude Code reads `CLAUDE.md`, which points here.

## Languages

rust

## Where the rules live

Detailed standards are in `.claude/rules/`:

- `common/`  — language-agnostic (coding style, testing, git, security)
- `rust/`  — rust-specific standards

How each tool loads them:

- **Claude Code** — via `CLAUDE.md`'s `@import` lines (loaded into context; not
  conditional on which file you're editing). Consult a language's other
  `*.md` files when working in that language.
- **Cursor** — the `paths:` frontmatter on each rule activates it by file glob.
  This is a Cursor feature; Claude Code ignores `paths:`.

## Project conventions

<!-- Fill these in — write what an AI can't infer from the code: -->
- **Tech stack:**
- **Build / run:**
- **Test:**       (coverage bar:    %)
- **Directory layout:**
- **Do NOT:**

---
> Source: [gocronx/matcher](https://github.com/gocronx/matcher) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-06-29 -->
