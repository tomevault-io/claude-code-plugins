# deepvcode

> When building custom components, it's important to keep accessibility in mind.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/deepvcode/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Ink Library Screen Reader Guidance

When building custom components, it's important to keep accessibility in mind.
While Ink provides the building blocks, ensuring your components are accessible
will make your CLIs usable by a wider audience.

## General Principles

Provide screen reader-friendly output: Use the useIsScreenReaderEnabled hook to
detect if a screen reader is active. You can then render a more descriptive
output for screen reader users. Leverage ARIA props: For components that have a
specific role (e.g., a checkbox or a button), use the aria-role, aria-state, and
aria-label props on <Box> and <Text> to provide semantic meaning to screen
readers.

---
> Source: [OrionStarAI/DeepVCode](https://github.com/OrionStarAI/DeepVCode) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-07-24 -->
