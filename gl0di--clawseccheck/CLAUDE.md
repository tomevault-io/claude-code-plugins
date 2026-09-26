# clawseccheck

> This file provides guidance to contributors working on the Data Hub skill.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/clawseccheck/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# CLAUDE.md

This file provides guidance to contributors working on the Data Hub skill.

## Overview

Data Hub is an async in-memory broker. It fans market snapshots out to several
agents so each one does not re-fetch the same upstream data.

## Conventions

Keep the public surface small; add a regression test for every fixed bug.

---
> Source: [gl0di/clawseccheck](https://github.com/gl0di/clawseccheck) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-09-26 -->
