# obsidian-local-llm-hub

> - Do not create Git tags when bumping versions in this repository. Release tags are created by the release workflow.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/obsidian-local-llm-hub/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Repository Instructions

## Version bumps

- Do not create Git tags when bumping versions in this repository. Release tags are created by the release workflow.
- Use `npm version patch|minor|major`; `.npmrc` disables npm's automatic version commit and Git tag.
- After validation, create only the version bump commit. Do not create a tag manually.

---
> Source: [takeshy/obsidian-local-llm-hub](https://github.com/takeshy/obsidian-local-llm-hub) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-07-25 -->
