# study-ios

> Swift/iOS learning project with interactive skills.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/study-ios/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# study-ios

Swift/iOS learning project with interactive skills.

## Skills

Skills are located in `.agents/skills/`. Each skill has a `SKILL.md` with instructions.

- `/swift-study` - Interactive Swift/iOS tutor (Socratic method)
- `/swift-quiz` - Adaptive quiz with 5 questions, difficulty 1-5
- `/study-summary` - Save learning notes from conversation to `notes/`

## Project Structure

- `notes/` - Saved learning notes (YYYY-MM-DD-topic.md format)
- `.agents/skills/` - Canonical skill definitions

## Conventions

- Bilingual support: Korean and English (user chooses at start)
- Code and Swift keywords always in English
- No emojis in output
- Learning progress tracked in memory or `notes/progress.md`

---
> Source: [ITlearning/study-ios](https://github.com/ITlearning/study-ios) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-02 -->
