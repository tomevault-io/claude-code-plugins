# debian-cosmic

> - **Sanitized Host:** Never perform builds directly on the host. Always use the provided Dockerfiles or the local Debian Testing chroot.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/debian-cosmic/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Project: Debian COSMIC

## 1. Core Mandates
- **Sanitized Host:** Never perform builds directly on the host. Always use the provided Dockerfiles or the local Debian Testing chroot.
- **Surgical Access:** Only mutate the `debian-cosmic` directory. Do not touch system paths unless explicitly requested.
- **Scratch Space:** Large builds and chroots MUST reside in `~/NoBackup/GEMINI_SCRATCH/` to prevent backup bloat.

## 2. Architecture: Atomic Switchboard
- **Primary Delivery:** `systemd-sysext` images delivered via GHCR.
- **Secondary Delivery:** Monorepo `.deb` packages for air-gapped or traditional installations.
- **Isolation:** `bwrap` and `systemd-nspawn` are used to ensure the COSMIC session does not pollute the host.

## 3. Workflows
- **Building Monodebs:** Use `just package-debs` from the root. This builds both Epoch and Utils in containers and extracts them to `dist/`.
- **Updating Recipes:** Modify the Dockerfiles in `images/cosmic-epoch/` or `images/cosmic-utils/`.

## 4. CI/CD Resource Optimization
- **Concurrency Control:** Workflows use `concurrency` groups mapped to `${{ github.workflow }}-${{ github.ref }}`.
- **Auto-Cancellation:** Pushing a new commit to a branch (e.g., `wip/*` or `main`) automatically cancels any existing in-flight builds for **that specific branch only**.
- **Isolation:** Builds on `main` are never interrupted by pushes to other branches, ensuring the production pipeline remains stable.

---
> Source: [rickysarraf/debian-cosmic](https://github.com/rickysarraf/debian-cosmic) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-09-18 -->
