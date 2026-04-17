# gemini-cli-palladius-public-goodies

> This extension contains Skills for Riccardo only but good enough to be published.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/gemini-cli-palladius-public-goodies/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

This extension contains Skills for Riccardo only but good enough to be published. 

* Emoji for title: yellow heart

## Schema and testing

Ensure the skills follow official Anthropic schema:https://mintlify.wiki/anthropics/skills/spec/metadata-schema 
Write a python test suite invokable with `just test` which checks for schema.
* FrontMatter MUST have name and description
* It should have a compatibility (for Gemini CLI).
* It should have a metadata.version.
Also a skill should have a CHANGELOG.md with its single-skill changes.
This is together with the overall CHANGELOG.md for the whole extension (which should track major changes and refactorings).
Remember, ebery single change unless purely cosmetical should result in a bump of extension version, or clients wont be ale to pull this change.

---
> Converted and distributed by [TomeVault](https://tomevault.io/claim/palladius) — claim your Tome and manage your conversions.
<!-- tomevault:4.0:claude_md:2026-04-10 -->
