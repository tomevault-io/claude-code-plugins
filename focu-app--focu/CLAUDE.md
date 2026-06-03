# project

> This rule explains the Focu project and structure

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/project/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# Focu 

Focu is an open-source mindful productivity app for macOS.

## Monorepo

Focu uses [Turbo](mdc:https:/turbo.build) to manage the monorepo structure.

- `apps/desktop`: The desktop app. Built with [Tauri](mdc:https:/tauri.app) and [NextJS](mdc:https:/nextjs.org). Embeds [Ollama](mdc:https:/ollama.com) to run the AI locally.
- `apps/landing-page`: The landing page. Built with [NextJS](mdc:https:/nextjs.org) and custom [TailwindUI](mdc:https:/tailwindui.com) components.
- `packages/ui`: The UI library. Mostly ReactJS, [Shadcn UI](mdc:https:/ui.shadcn.com) and some [Tremor components](mdc:https:/tremor.so).

## Main Libraries

The project uses the following technologies, make sure to not reference APIs or functions from other versions.

- NodeJS v20
- NextJS v14
- Tauri v2
- React v18

---
> Source: [focu-app/focu](https://github.com/focu-app/focu) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-06-03 -->
