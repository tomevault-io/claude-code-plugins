# gitignore-requirements

> Gitignore File Requirements

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/gitignore-requirements/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Gitignore Requirements

## Specifications
- MUST ignore all the usual files and folders including:

# environment artifacts
.venv
.env
venv/
venv.bak/
.vscode/
.DS_Store
Pipfile
Pipfile.lock

# python artifacts
__pycache__
*.egg-info
dist/
.mypy_cache/
.pytest_cache/

# build
build/
poetry.lock
dist

# examples
chatlog.txt
output_*.wav

---
> Source: [deepgram-starters/flask-voice-agent](https://github.com/deepgram-starters/flask-voice-agent) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-09-09 -->
