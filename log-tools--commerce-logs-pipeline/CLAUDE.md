# commerce-logs-pipeline

> If Docker is not available, the usual `make dev-up` workflow cannot start Kafka. Instead run a local broker manually.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/commerce-logs-pipeline/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Working with Kafka without Docker

If Docker is not available, the usual `make dev-up` workflow cannot start Kafka. Instead run a local broker manually.

The broker listens on `localhost:9092`. Check `kafka.log` for startup progress.

## Verifying Connectivity
- Test with the pipeline tool:
  ```bash
  cd pipeline/ingest
  go run . test-kafka
  ```
- Or list topics directly:
  ```bash
  $KAFKA_DIR/bin/kafka-topics.sh --bootstrap-server localhost:9092 --list
  ```

---
> Converted and distributed by [TomeVault](https://tomevault.io/claim/Log-Tools)
> This is a context snippet only. You'll also want the standalone SKILL.md file — [download at TomeVault](https://tomevault.io/claim/Log-Tools)
<!-- tomevault:4.0:claude_md:2026-04-08 -->
