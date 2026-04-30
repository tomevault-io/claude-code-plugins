# wyoming-pocket-tts

> - Use `uv` for all dependency management (`uv add`, `uv run`). Never use `requirements.txt`.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/wyoming-pocket-tts/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Agent Guidelines

- Use `uv` for all dependency management (`uv add`, `uv run`). Never use `requirements.txt`.
- Python 3.10+. Use modern type annotations where compatible with 3.10 (`list`, `dict`, not `List`, `Dict`).
- Before committing: run `prek run --all-files` and `uv run -m pytest`. All hooks and tests must pass.
- This is a Wyoming protocol TTS server for Home Assistant. Changes must maintain compatibility with the Wyoming protocol and Home Assistant add-on system.
- The project uses Kyutai's Pocket TTS model. Voice handling (preset + custom) is in `wyoming_pocket_tts/handler.py`.

---
> Source: [araa47/wyoming_pocket_tts](https://github.com/araa47/wyoming_pocket_tts) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-04-25 -->
