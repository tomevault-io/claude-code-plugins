# trafficserver-ingress-controller

> This file provides guidance to coding agents working with this repository.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/trafficserver-ingress-controller/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# AGENTS.md

This file provides guidance to coding agents working with this repository.

## Project Overview

Apache Traffic Server Ingress Controller is a Kubernetes ingress controller for Apache Traffic Server (ATS). It watches `Ingress` / `Service` / `Endpoints` resources and translates them into ATS `remap.config` / `plugin.config` configuration; an admission webhook validates Ingress resources before the API server admits them.

## Security model

For security scans, vulnerability triage, security reviews, and any change touching the admission webhook, ingress-to-`remap.config` translation, RBAC, or how Kubernetes API objects cross the trust boundary, read [`SECURITY.md`](./SECURITY.md) first. The repo-specific surfaces (admission webhook, ingress routing) are documented there in addition to the umbrella model at [apache/trafficserver/SECURITY.md](https://github.com/apache/trafficserver/blob/master/SECURITY.md).

---
> Source: [apache/trafficserver-ingress-controller](https://github.com/apache/trafficserver-ingress-controller) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-07-22 -->
