# help-ui-index

> Keep Help Assistant UI index in sync when adding locatable controls

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/help-ui-index/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# Help Assistant UI index

When you add or change a locatable control, put a stable hook on the element:

- `data-setting-key` — Admin setting (same key as `settings` / Admin search)
- `data-tour-id` — board/chrome control (tour + Help Go there)
- `data-help-target` — Profile or one-off Help targets
- `data-owner-setup` — Configuration guide field

Then regenerate and commit the index:

```
npm run help:ui-index
```

CI runs `npm run help:ui-index:check`. Do not hand-edit `server/config/helpUiIndex.generated.json`.

Behavioral exceptions (defaults vs live prefs, soft WIP, trash vs archive) go in `server/config/helpAssistantFacts.js`, not in EN/FR catalog rows.

---
> Source: [drenlia-inc/agila](https://github.com/drenlia-inc/agila) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-08-15 -->
