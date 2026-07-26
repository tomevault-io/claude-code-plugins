# markdowneditor2022

> - When a user says a fix did not work, immediately verify in-workspace behavior and adjust instead of only applying the first likely change.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/markdowneditor2022/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Copilot Instructions

## Project Guidelines

- When a user says a fix did not work, immediately verify in-workspace behavior and adjust instead of only applying the first likely change.
- When applying external guidance, adapt registry/settings snippets to this extension's own editor identifiers instead of copying them verbatim. Ensure that external registration advice aligns with the compile-time generated editor registration via ProvideEditorExtension/ProvideEditorFactory attributes.
- When editing a .csproj file, unload the project from the solution in the IDE, make the necessary changes, and then reload the project to ensure the changes take effect properly.

---
> Source: [madskristensen/MarkdownEditor2022](https://github.com/madskristensen/MarkdownEditor2022) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-07-24 -->
