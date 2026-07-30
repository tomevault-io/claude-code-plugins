# build-applications-w-copilot-agent-mode

> Use commands that target `octofit-tracker/frontend` without changing directories.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/build-applications-w-copilot-agent-mode/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Octofit Tracker React Presentation Tier Guidelines

Use commands that target `octofit-tracker/frontend` without changing directories.

```bash
npm create vite@latest octofit-tracker/frontend -- --template react
npm install --prefix octofit-tracker/frontend
npm install bootstrap react-router-dom --prefix octofit-tracker/frontend
```

Add Bootstrap CSS import at the top of `octofit-tracker/frontend/src/main.jsx`.

## Images

Use `docs/octofitapp-small.png` for the app logo.

---
> Source: [skills/build-applications-w-copilot-agent-mode](https://github.com/skills/build-applications-w-copilot-agent-mode) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-07-27 -->
