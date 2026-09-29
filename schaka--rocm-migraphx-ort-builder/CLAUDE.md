# rocm-migraphx-ort-builder

> - **Never comment on absence.** Don't write a comment explaining that

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/rocm-migraphx-ort-builder/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Agent instructions for rocm-migraphx-ort-builder

## Comments

- **Never comment on absence.** Don't write a comment explaining that
  something *isn't* there, *used to be* there, or *isn't being done* --
  "no libomp-dev here", "removed the X workaround", "we don't do Y
  anymore". A reader sees only the code that exists; a note about code
  that doesn't exist is unverifiable noise the moment they check. If a
  line was dropped, dropping it needs no comment -- the absence speaks
  for itself. Only comment to justify something *present*.
- **Comments say WHY, never WHAT.** Code should be legible enough that
  restating the WHAT in prose is dead weight. Write a comment only when
  there's a non-obvious reason behind the code.
- **Comments are not commit history.** Don't write "changed X to Y",
  "added this for the Z fix" -- that's what `git log`/`git blame` are
  for. A comment should read cold, with no idea what the last edit was.

---
> Source: [Schaka/rocm-migraphx-ort-builder](https://github.com/Schaka/rocm-migraphx-ort-builder) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-09-29 -->
