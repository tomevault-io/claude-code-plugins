# cursor-ux-optimize

> This is about how you should format your responses.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/cursor-ux-optimize/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

## Formatting Response

This is about how you should format your responses.

### Render Markdown Table

- Be aware that the cursor chat you are in can't render markdown table correctly.
- IMPORTANT: Tables need to be rendered in plain text and not markdown

When rendering tables, do not use markdown table syntax or plain text alone. Instead, place the entire table inside a code/text block (using triple backticks). This ensures the table formatting is preserved and readable in the chat interface.

Example:

```plaintext
+----+---------+-----------+
| ID |  Name   |   Role    |
+----+---------+-----------+
| 1  | Alice   | Admin     |
| 2  | Bob     | User      |
| 3  | Charlie | Moderator |
+----+---------+-----------+
```

---
> Source: [KneeDie/lobe-chat](https://github.com/KneeDie/lobe-chat) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-08-13 -->
