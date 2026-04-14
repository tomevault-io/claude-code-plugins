# docker-development-skill

> ├── skills/docker-development/

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/docker-development-skill/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# AGENTS.md — docker-development-skill

## Repo Structure

```
.
├── skills/docker-development/
│   ├── SKILL.md                        # Main skill definition
│   ├── checkpoints.yaml                # Evaluation checkpoints
│   └── references/
│       ├── ci-testing.md               # CI testing patterns for containers
│       └── dind-testing-patterns.md    # Docker-in-Docker testing patterns
├── Build/
│   ├── Scripts/
│   │   └── check-plugin-version.sh     # Version validation script
│   └── hooks/
│       └── pre-push                    # Git pre-push hook
├── evals/
│   └── evals.json                      # Evaluation definitions
├── .github/workflows/                  # CI workflows
├── composer.json                       # PHP package metadata
├── docs/                               # Architecture and planning docs
│   ├── ARCHITECTURE.md
│   └── exec-plans/
├── scripts/
│   └── verify-harness.sh              # Harness verification script
└── README.md
```

## Commands

- `bash scripts/verify-harness.sh --format=text --status` — check harness maturity level
- `bash Build/Scripts/check-plugin-version.sh` — validate plugin version consistency

## Rules

1. **Minimal images** — use Alpine or distroless base images with multi-stage builds.
2. **Security first** — run as non-root USER, never bake secrets into layers, pin versions.
3. **No security anti-patterns** — no `chmod 777`, no `privileged: true`, no host root mounts, no `0.0.0.0` binding, no secrets in ENV/ARG.
4. **Cache-efficient** — copy dependency files (package.json, go.mod) before source code; combine RUN commands; clean apt cache in same layer.
5. **Testable** — all images must be verifiable in CI; bypass entrypoints with `--entrypoint`.
6. **CI testing**: create `.env` from `.env.example` before `docker compose config`.
7. **Mock upstream DNS** with `--add-host` when testing nginx configs in isolation.
8. **BuildKit secrets** — use `--mount=type=secret` for private repos, never `ENV`/`COPY` secrets.

## References

- [SKILL.md](skills/docker-development/SKILL.md) — full skill definition
- [CI Testing](skills/docker-development/references/ci-testing.md) — CI testing patterns
- [DinD Patterns](skills/docker-development/references/dind-testing-patterns.md) — Docker-in-Docker testing

---
> Converted and distributed by [TomeVault](https://tomevault.io/claim/netresearch) — claim your Tome and manage your conversions.
<!-- tomevault:4.0:claude_md:2026-04-11 -->
