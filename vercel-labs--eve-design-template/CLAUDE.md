# eve-design-template

> This repository is a generic, Slack-only design-agent template built with Eve.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/eve-design-template/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Working on this template

This repository is a generic, Slack-only design-agent template built with Eve.

- Read `node_modules/eve/docs/` before changing Eve APIs.
- Keep runtime knowledge closed to the approved files under `knowledge/`.
- Keep the runtime read-only: no shell, file writes, web access, connections, or delegation.
- Do not add organization-specific names, rules, links, tokens, or examples.
- Pin dependency versions exactly.
- Run `pnpm check` before opening a pull request.
- Update `BOOTSTRAP.md`, `REFRESH.md`, and `README.md` when setup behavior changes.

---
> Source: [vercel-labs/eve-design-template](https://github.com/vercel-labs/eve-design-template) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-07-25 -->
