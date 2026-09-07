# mobile-dashboard

> - Flutter mobile dashboard application

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/mobile-dashboard/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# AGENTS.md

Project:
- Flutter mobile dashboard application

Stack:
- Flutter
- Dart
- Firebase
- Firestore
- Firebase Auth
- Firebase Cloud Messaging

Architecture:
- MVC Architecture


State Management:
- Riverpod

Routing:
- GoRouter

Rules:
- No GetX
- No business logic inside widgets
- No direct Firestore access in UI layer
- All Firebase calls go through repositories

UI:
- Responsive layouts mandatory
- Tablet support required
- Dark mode support required

Performance:
- Paginate Firestore queries
- Avoid unnecessary rebuilds
- Use streams efficiently

AI contributors must follow:
- AGENTS.md
- .agents/*

---
> Source: [lancemiranoo/mobile-dashboard](https://github.com/lancemiranoo/mobile-dashboard) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-09-06 -->
