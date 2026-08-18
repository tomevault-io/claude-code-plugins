# turnleaf

> - `RELEASE_NOTES.md` is the canonical release-notes source.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/turnleaf/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Agent Notes

- `RELEASE_NOTES.md` is the canonical release-notes source.
- Keep the `## Unreleased` section current.
- A local git hook amends each commit with a `RELEASE_NOTES.md` update from the commit subject when hooks are installed.
- Use `npm run release:notes` to extract the release body for GitHub releases.
- Keep changes small and explicit; do not add abstractions unless they solve a real problem.

---
> Source: [sgerner/turnleaf](https://github.com/sgerner/turnleaf) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-08-17 -->
