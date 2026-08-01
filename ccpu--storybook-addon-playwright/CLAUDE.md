# storybook-addon-playwright

> This file provides instructions for the MCP Browser and how to use it effectively.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/storybook-addon-playwright/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


When a code change in the addon needs to be tested or viewed in the browser, rebuild and rerun the addon first, then refresh the browser to see the changes. Hot reload does not work reliably for components or code used inside the addon.

Alternatively, create Storybook stories for the components and test them in Storybook. Hot reload works there and it is faster for iterating on changes.

---
> Source: [ccpu/storybook-addon-playwright](https://github.com/ccpu/storybook-addon-playwright) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-07-26 -->
