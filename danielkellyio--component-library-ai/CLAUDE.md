# docs

> Rules for writing documentation

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/docs/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

## General 
Docs are always written in `content/components` and `content/blocks`

Their frontmatter includes:

* name - The component name
* description - A short sentence description of the component 

Do NOT include an h1 (#) in the body

## Order of Sections

* General Overview
* Props - table of props (columns - Prop, Type, Default, Description)
* Slots - table of slots (columns - Name, Props, Description)
* Events - table of events (columns - Event, Payload, Description)
* Basic Usage
* More Examples

---
> Source: [danielkellyio/component-library-ai](https://github.com/danielkellyio/component-library-ai) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-15 -->
