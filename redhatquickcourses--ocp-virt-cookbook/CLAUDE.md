# security-policy

> Credential handling, context exclusions, and cluster safety rules

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/security-policy/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# Security Policy

## Context Exclusions

The following file patterns must never be read, displayed, included in context, or committed:

- `**/kubeconfig`
- `**/kubeconfig.*`
- `**/.env`
- `**/.env.*`
- `**/secrets/**`
- `**/*.pem`
- `**/*.key`

## Credential Handling

- Only use the kubeconfig path the user explicitly provides. Never read or display its contents.
- No secrets, tokens, passwords, or credentials in commits or documentation.
- If a tutorial requires credentials (e.g., pull secrets), use placeholder values and document that the user must substitute their own.

## Cluster Safety

- MCP servers run with minimal required permissions.
- Never modify cluster-wide resources (CRDs, cluster roles, nodes) without explicit human confirmation.
- Never delete resources that were not created during the current session.

---
> Source: [RedHatQuickCourses/ocp-virt-cookbook](https://github.com/RedHatQuickCourses/ocp-virt-cookbook) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-31 -->
