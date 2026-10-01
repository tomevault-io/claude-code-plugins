# never-edit-uefn-digests

> HARD — never edit UEFN digests; Verse build then look inside (UEFN auto-edits them)

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/never-edit-uefn-digests/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# UEFN digests — READ ONLY; UEFN auto-edits them

**NEVER** write, edit, delete, rename, or `workspace_write_file` any `*.digest.verse`
(Fortnite / Verse / UnrealEngine / Assets).

**UEFN rewrites digests itself** on Verse build / import. You do not touch the files.

## Workflow

1. Write project code under `Content/Verse/**/*.verse` only.
2. When UEFN is open: `workspace_compile_verse` (Verse build).
3. Then **look inside** digests: `list_verse_digests` → `search_verse_digest` /
   `get_verse_api` / `list_verse_types` (Assets digest especially after new
   materials / meshes / prefabs).

Missing a type? Build first, then re-search — never invent by patching a digest.

---
> Source: [UEFN-Ducky/UEFN-Ducky](https://github.com/UEFN-Ducky/UEFN-Ducky) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-09-30 -->
