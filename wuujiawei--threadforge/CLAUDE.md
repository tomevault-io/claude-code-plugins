# threadforge

> - If the task involves release, publish, tag, changelog, or Maven Central, read `docs/releases.md` first.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/threadforge/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# ThreadForge Agent Index

- If the task involves release, publish, tag, changelog, or Maven Central, read `docs/releases.md` first.
- Treat real version tags as real releases, not dry runs.
- Keep the changelog entry visible near the top of `README.md`.
- If Central fails on signature validation, compare the current signature with the previous successful release before retrying.
- In repository docs, use relative paths only. Do not write workstation-specific absolute paths, local usernames, key material, fingerprints, or other sensitive environment-specific data.

---
> Source: [wuuJiawei/ThreadForge](https://github.com/wuuJiawei/ThreadForge) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-04-21 -->
