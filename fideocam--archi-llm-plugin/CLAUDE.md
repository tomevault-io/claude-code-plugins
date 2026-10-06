# commit-build-push

> Commit and push always include a Maven plugin build

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/commit-build-push/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# Commit and push with build

When the user asks to commit, push, or both, also run `scripts/mvn-with-archi.sh clean package` (do not skip tests unless they ask). After a successful build, if `export/latest/ArchiGPT.archiplugin` changed, commit that zip too, then push. Do not create a GitHub release unless they ask.

---
> Source: [fideocam/Archi-LLM-plugin](https://github.com/fideocam/Archi-LLM-plugin) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-10-06 -->
