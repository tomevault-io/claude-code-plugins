# 00-core

> Core product rules for Subber

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/00-core/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# Core

Desktop app locale: qualsiasi video parlato → trascrizione fedele → traduzione editoriale opzionale → SRT DaVinci.

Stack: Tauri 2 + React + TS + Rust + FFmpeg + worker Python (faster-whisper). Architettura minima. Niente test framework, CI, microservizi, Docker, astrazioni premature.

Un task alla volta, app avviabile dopo ogni task. Prima di scrivere: leggi il codice esistente e integra. Non duplicare logica. Non anticipare il task N+1.

Non lanciare install/build/server/modelli. Elenca i comandi all’utente.

Dettaglio: `AGENTS.md`.

---
> Source: [AndreaZero/subber](https://github.com/AndreaZero/subber) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-08-28 -->
