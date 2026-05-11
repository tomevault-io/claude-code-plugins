# k8s

> Kubernetes manifest standards

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/k8s/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# K8s
api:feature-gates for alpha/beta|version-dependent→state assumptions
manifest:resource limits req|probes req|configmap/secret via env not vol
security:no plain secrets|RBAC minimal|network policies|pod security standards
operator:reconcile idempotent|status subresource|finalizers for cleanup|leader election
helm:values schema|README|upgrade path tested

---
> Source: [ArangoGutierrez/promptsLibrary](https://github.com/ArangoGutierrez/promptsLibrary) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-08 -->
