# impl-files

> Implementation file guard — reminds the agent to verify pipeline state before editing app/ or tests/

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/impl-files/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


You are editing implementation files. Before making any changes, verify the MAPLE pipeline is active:

```bash
python3 -c "import json; s=json.load(open('.claude/state/maple.json')); print(s.get('stage',''), s.get('status',''))" 2>/dev/null || echo "no pipeline"
```

If status is not `RUNNING` or `PAUSED`, stop and start the pipeline first via `/pipeline-runner <name>`. Do not write to these files outside a pipeline stage.

---
> Source: [kinncj/Heimdall](https://github.com/kinncj/Heimdall) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-06-27 -->
