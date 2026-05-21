# 01-project-overview

> This Chrome extension provides Arc browser-like sidebar functionality for managing tabs, spaces, and bookmarks. It organizes browser tabs into spaces (tab groups) and allows users to:

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/01-project-overview/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Arcsidebar Chrome Extension Overview

This Chrome extension provides Arc browser-like sidebar functionality for managing tabs, spaces, and bookmarks. It organizes browser tabs into spaces (tab groups) and allows users to:

- Create and manage multiple spaces (similar to Arc's Spaces)
- Save tabs as bookmarks within spaces
- Easily switch between spaces
- Archive and restore tabs
- Drag and drop tabs between spaces or within a space

## Key Files

- [sidebar.js](mdc:sidebar.js) - The main UI and functionality implementation
- [chromeHelper.js](mdc:chromeHelper.js) - Helper functions for Chrome API interactions
- [localstorage.js](mdc:localstorage.js) - Storage management for persistent data
- [utils.js](mdc:utils.js) - Utility functions used throughout the extension
- [icons.js](mdc:icons.js) - SVG icon definitions for the UI

---
> Source: [nisargkolhe/arcify](https://github.com/nisargkolhe/arcify) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-20 -->
