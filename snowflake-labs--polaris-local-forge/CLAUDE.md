# yaml-schemas

> Files that are Taskfile YAML format (NOT Kubernetes/RKE configs):

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/yaml-schemas/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# YAML File Types in This Project

## Taskfiles (go-task)

Files that are Taskfile YAML format (NOT Kubernetes/RKE configs):

- `Taskfile.yml` - Main taskfile
- `taskfiles/*.yml` - Included taskfiles (cluster.yml, catalog.yml, etc.)

**Valid properties:** `version`, `silent`, `vars`, `env`, `includes`, `tasks`

## Ansible Playbooks

Files that are Ansible playbooks (NOT Snowflake manifests):

- `polaris-forge-setup/*.yml` - Ansible playbooks
- `polaris-forge-setup/defaults/*.yml` - Ansible defaults
- `polaris-forge-setup/templates/*.j2` - Jinja2 templates

**Valid structure:** `hosts`, `tasks`, `vars`, `vars_files`, `handlers`

## Kubernetes Manifests

- `k8s/**/*.yaml` - Kubernetes resources (generated)
- `polaris-forge-setup/files/*.yaml` - K8s template sources

## IDE Schema Warnings

If you see lint errors like:
- "Property tasks is not allowed" on Taskfiles
- "Expected Snowflake Application Package Manifest" on Ansible files

These are **false positives** from incorrect schema auto-detection. The files are valid.

---
> Source: [Snowflake-Labs/polaris-local-forge](https://github.com/Snowflake-Labs/polaris-local-forge) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-21 -->
