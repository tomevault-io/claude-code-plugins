# 01-pipeline

> Transcription and translation pipeline

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/01-pipeline/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# Pipeline

Ordine fisso:

`video → FFmpeg audio → faster-whisper (task=transcribe) → traduzione contestuale su blocchi se le lingue differiscono → formatter SRT → export`

Mai tradurre l’audio in un unico passaggio. Non usare Whisper `task=translate` come unico output.

Traduzione su contesto: segmento precedente + corrente + successivo.

Output per video: `{nome}.{lang}.txt`, `{nome}.{lang}.srt`, `{nome}.{output}.srt`, `{nome}.json`.

JSON minimo: `start`, `end`, testo sorgente, testo tradotto, `speaker` se c’è, `confidence` se c’è.

Glossario vincola ASR e traduzione: non alterare e non tradurre male i termini protetti.

---
> Source: [AndreaZero/subber](https://github.com/AndreaZero/subber) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-08-28 -->
