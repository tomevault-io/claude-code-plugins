# verso

> - Write commit messages, code comments, identifiers, documentation, pull request titles, and pull request descriptions in English.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/verso/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Repository Guidelines

## Language

- Write commit messages, code comments, identifiers, documentation, pull request titles, and pull request descriptions in English.
- User-facing localization resources and translated book content may use their target language.

## Git and GitHub

- Use Conventional Commits for pull request titles, for example `feat: add keyboard navigation`.
- Keep commit messages concise and written in English.
- Sign commits cryptographically and include a DCO sign-off whenever the local environment supports both.

## Validation

- Run `npm run lint` before publishing changes.
- Run `npm test` for changes that affect application behavior, storage, rendering, or build configuration.
- Keep the local development server bound to `0.0.0.0` so the application remains reachable from the LAN.

## Product Constraints

- Keep uploaded books, page indexes, and translation results in Docker volume-backed local storage rather than browser caches or cloud services.
- Preserve lazy PDF rendering and bounded translation concurrency for large scanned books.
- Keep interface locale independent from the translation target language.

---
> Source: [MrCroxx/Verso](https://github.com/MrCroxx/Verso) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-08-28 -->
