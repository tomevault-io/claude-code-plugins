# tinta

> - For every feature or compatibility extension, add or update runnable Markdown files in `tests/fixtures/` that demonstrate the new behavior.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/tinta/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Feature validation workflow

- For every feature or compatibility extension, add or update runnable Markdown files in `tests/fixtures/` that demonstrate the new behavior.
- Include mixed documents: combine the feature with existing headings, tables, lists, emphasis, links, quotes and code where applicable. Check surrounding content as well as the feature itself.
- Exercise the fixtures in the built Tinta app using computer use or the native rendering/export harnesses. For layout changes, inspect rendered output at normal and narrow widths, and check relevant themes and exports. Record what was actually checked and any remaining limitations.
- Add meaningful automated regression checks for parser structure or layout failures found in these documents. Keep generated screenshots and exports in an ignored build/output directory.
- When working on a GitHub issue, reference it in completed commits. Do not automatically reply to the reporter; provide a draft reply for the maintainer when finished.

---
> Source: [oipoistar/tinta](https://github.com/oipoistar/tinta) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-09-13 -->
