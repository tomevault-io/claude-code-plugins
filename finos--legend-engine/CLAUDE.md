# legend-engine

> Pure Maven modules do not support reliable incremental lifecycle builds. After changing

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/legend-engine/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Agent Build Guidance

## Maven workflow for Pure modules

Pure Maven modules do not support reliable incremental lifecycle builds. After changing
Pure or module sources, rebuild the directly touched module from the repository root with:

```bash
mvn clean install -DskipTests -pl <module-path>
```

The `clean` is required because stale Pure PAR/generated-repository state can cause errors such
as `The code repository ... already exists`.

When no source files have changed and only a test rerun is needed, bypass the Maven lifecycle and
invoke Surefire directly so Pure source compilation, PAR generation, Java code generation, and test
compilation are not repeated:

```bash
mvn -pl <module-path> org.apache.maven.plugins:maven-surefire-plugin:2.22.2:test
```

Direct Surefire runs assume the module was previously clean-installed and its `target/` outputs are
current. Do not use `-am` or rebuild dependents unless explicitly requested.

---
> Source: [finos/legend-engine](https://github.com/finos/legend-engine) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-09-24 -->
