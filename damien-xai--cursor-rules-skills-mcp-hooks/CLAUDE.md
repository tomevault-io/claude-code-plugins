# ui-security

> UI security for Svelte components (XSS, no secrets in the client)

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/ui-security/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# UI security

This is an **Apply to Specific Files** rule. It attaches on `**/*.svelte`.

- Render user text with `{value}`. Do not use `{@html}` for untrusted input.
- Never put API keys, tokens, or passwords in pages or `$lib/components`.
- Read secrets only on the server (`$lib/server/`, `+server.ts`, `+page.server.ts`).
- Keep mutations behind `/api/` `fetch` calls; do not import `$lib/server/*` from the client.

---
> Source: [damien-xai/cursor-rules-skills-mcp-hooks](https://github.com/damien-xai/cursor-rules-skills-mcp-hooks) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-09-14 -->
