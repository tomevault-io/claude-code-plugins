# forq-cli

> - After all changes are made, ALWAYS build the project with `npm run build`. Ignore warnings, fix errors.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/forq-cli/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

- After all changes are made, ALWAYS build the project with `npm run build`. Ignore warnings, fix errors.
- Always add a one-sentence summary of changes to `.cursor-updates` file in markdown format at the end of every agent interaction.
- If you forget, the user can type the command "finish" and you will run the build and update `.cursor-updates`.
- Finally, update git with `git add . && git commit -m "..."`. Don't push.

---
> Source: [kleneway/forq-cli](https://github.com/kleneway/forq-cli) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-22 -->
