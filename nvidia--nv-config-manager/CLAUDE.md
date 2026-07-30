# helm-testing

> Helm chart conventions for the nv-config-manager project

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/helm-testing/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# Helm Chart Conventions

## Template Testing

When running `helm template` for testing or dry-run validation, always use `values-ci.yaml`:

```bash
helm template test . --values values-ci.yaml
```

Do NOT use `values.yaml` alone — it requires secrets/vault paths that aren't populated outside of a real deployment. `values-ci.yaml` provides the necessary overrides for local and CI testing.

## Observability Values

To test with the observability stack enabled, layer `values-observability.yaml` on top:

```bash
helm template test . --values values-ci.yaml --values values-observability.yaml
```

---
> Source: [NVIDIA/nv-config-manager](https://github.com/NVIDIA/nv-config-manager) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-07-29 -->
