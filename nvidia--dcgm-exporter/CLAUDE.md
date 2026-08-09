# dcgm-exporter

> Metric CSV, exporter counter, and Prometheus exposition contracts

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/dcgm-exporter/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# Metrics Contracts

- Metric CSV rows have exactly three fields: field name, Prometheus type, help.
- Exporter-owned counters must stay aligned across code, CSV examples, docs,
  tests, and `llms.txt`.
- Do not invent metric names or labels.
- Prometheus families must have stable HELP/TYPE metadata and unique label
  sets.
- Run `go test ./internal/pkg/counters` after metric guidance or counter
  changes.

---
> Source: [NVIDIA/dcgm-exporter](https://github.com/NVIDIA/dcgm-exporter) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-08-09 -->
