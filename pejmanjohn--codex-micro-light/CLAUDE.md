# codex-micro-light

> - Keep the installable plugin at `plugins/codex-micro-light` and its manifest at `.codex-plugin/plugin.json`.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/codex-micro-light/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Repository guidance

- Keep the installable plugin at `plugins/codex-micro-light` and its manifest at `.codex-plugin/plugin.json`.
- Keep the reusable skill source at `plugins/codex-micro-light/skills/setmicrolight`.
- Preserve the exact skill name `setmicrolight` and plugin name `codex-micro-light`.
- Keep automated tests hardware-free. Never open the HID device from CI or a unit test.
- Run `node --test test/*.test.cjs` after changing scripts, targeting, concurrency, manifests, or packaging.
- Run `node scripts/validate-repository.cjs` before committing public metadata changes.
- Run the Plugin Creator validator and Skill Creator validator when those built-in skills are available.
- Treat the HID protocol as private and experimental. Do not claim official OpenAI or Work Louder support.
- Keep the public repository URL `https://github.com/pejmanjohn/codex-micro-light` aligned across `README.md` and `.codex-plugin/plugin.json`.

---
> Source: [pejmanjohn/codex-micro-light](https://github.com/pejmanjohn/codex-micro-light) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-07-24 -->
