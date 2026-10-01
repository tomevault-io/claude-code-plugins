# viberaven

> Apply when editing Stripe, Polar, or payment webhook handlers

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/viberaven/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


Before editing these files, read `.viberaven/agent-context.md` and `.viberaven/mission-map.md`.

A payment webhook handler should verify the provider signature over the raw request body before trusting the event. After webhook edits, `npx -y viberaven@1.5.3 check` shows whether a Stripe handler does.

---
> Source: [ohad6k/VibeRaven](https://github.com/ohad6k/VibeRaven) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-10-01 -->
