# mtpy-v2

> Always use the **`py313` conda environment** to run Python commands and tests.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/mtpy-v2/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# MTpy-v2 Copilot Instructions

## Python / Test Environment

Always use the **`py313` conda environment** to run Python commands and tests.

The conda executable is at:
```
C:\Users\peaco\miniconda3\Scripts\conda.exe
```

### Running tests
```powershell
& "C:\Users\peaco\miniconda3\Scripts\conda.exe" run -n py313 python -m pytest <args>
```

### Running arbitrary Python
```powershell
& "C:\Users\peaco\miniconda3\Scripts\conda.exe" run -n py313 python -c "<code>"
```

### Running a script
```powershell
& "C:\Users\peaco\miniconda3\Scripts\conda.exe" run -n py313 python <script.py>
```

Never use bare `python` or `python3` — they are not on PATH. Always prefix with the conda run command above.

---
> Source: [MTgeophysics/mtpy-v2](https://github.com/MTgeophysics/mtpy-v2) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-09-10 -->
