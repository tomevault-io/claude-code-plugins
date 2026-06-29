# react-native-svg-app-icon

> The cache enables incremental builds by tracking hashes of input and output files across runs. `CacheSession` is created per generation run with the input file buffers and a `force` flag.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/react-native-svg-app-icon/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Cache

The cache enables incremental builds by tracking hashes of input and output files across runs. `CacheSession` is created per generation run with the input file buffers and a `force` flag.

For each output file, `isUpToDate()` checks whether the package version, input hashes, and output hash all match the stored cache. If so, the file is skipped. After writing a file, `recordBuffer()` records its hash in memory. At the end of the run, `flush()` persists the updated cache.

Cache data is stored as JSON in a temp directory (`os.tmpdir()/react-native-svg-app-icon/<project-hash>/cache.json`), keyed by a hash of `projectRoot`.

---
> Source: [aeirola/react-native-svg-app-icon](https://github.com/aeirola/react-native-svg-app-icon) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-06-29 -->
