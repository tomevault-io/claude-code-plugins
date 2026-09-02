# agentconfigscore

> Keep the runtime dependency-free on Python 3.10+.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/agentconfigscore/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Agent instructions — AgentConfigScore

Keep the runtime dependency-free on Python 3.10+.

## Verification

- Run `PYTHONPATH=src python -m unittest discover -s tests -v` after scanner or CLI changes.
- Run `PYTHONPATH=src python -m agent_config_score.cli examples/demo` when changing scoring or output formatting.

## Scope

- Put scanning and scoring logic in `src/agent_config_score/scanner.py`.
- Keep CLI argument parsing and terminal output in `src/agent_config_score/cli.py`.
- Add a regression test for every false positive or false negative that is fixed.

## Safety

- Never print the full value of a detected credential.
- Keep contradiction detection conservative; do not claim semantic conflicts without strong evidence.

---
> Source: [LE0-Lin/AgentConfigScore](https://github.com/LE0-Lin/AgentConfigScore) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-09-02 -->
