# mcsmanager

> Frontend (Vue 3) development conventions

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/mcsmanager/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# Vue component conventions

- Use **Vue 3**. Components must use `<script setup lang="ts">`. Use `const` and clear types to express intent.
- Pass data via Vue’s recommended **props**; do not break one-way data flow.
- Keep component TS logic short. Move complex logic into dedicated **hooks** by responsibility for reuse.
- Keep templates short. Extract complex markup into separate Vue components for reuse.

---
> Source: [MCSManager/MCSManager](https://github.com/MCSManager/MCSManager) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-07-26 -->
