# writing-code-protocol

> Writing Code Protocol

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/writing-code-protocol/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


**Writing Code Protocol**

- Place mock, test and implementation exactly near intent file.
- Export files from its folders using barrel file (ui/ui.dart, commands/commands.dart etc.).
- To find implementation, try to load intents first.
- Do not rely on strings, use enums.
- Use context.read/context.select to subscribe to observable state in build methods.
- If you create new file, make sure to check its intent. If it doesn't have an intent - create it.
- Use EquatableMixin for classes.

---
> Source: [Arenukvern/mcp_flutter](https://github.com/Arenukvern/mcp_flutter) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-18 -->
