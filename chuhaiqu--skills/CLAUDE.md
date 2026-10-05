# skills

> - Treat the directory passed to the sync command as the only canonical content source.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/skills/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Repository instructions

- Treat the directory passed to the sync command as the only canonical content source.
- Never import transcripts, private source maps, guest-review packets, credentials, local absolute paths, or internal-only files.
- Preserve copied source files byte-for-byte. Put workflow interpretation in `SKILL.md`, not in the source references.
- Keep every skill independently installable and focused on a concrete user job.
- Keep `SKILL.md` below 500 lines with only `name` and `description` in frontmatter.
- When source content changes, run the sync and full validation before committing.
- Do not weaken or replace the repository license without explicit authorization from Velocity1, LLC.

---
> Source: [chuhaiqu/skills](https://github.com/chuhaiqu/skills) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-10-05 -->
