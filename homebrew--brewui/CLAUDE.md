# doc-relative-links

> Use relative links when docs reference repo doc files.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/doc-relative-links/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# Doc-to-doc Links

- When one Markdown document references another documentation file in this repository, use a relative Markdown link (for example, `[ARCHITECTURE.md](./ARCHITECTURE.md)`).
- Do not use absolute GitHub `https://github.com/.../blob/...` links for intra-repo documentation references.
- Use path-correct relative links for subdirectories (for example, from `.ai/memory.md` to `../ARCHITECTURE.md`).

---
> Source: [Homebrew/BrewUI](https://github.com/Homebrew/BrewUI) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-06-16 -->
