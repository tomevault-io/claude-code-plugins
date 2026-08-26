# vx-testing

> Testing conventions for vx: test file locations, frameworks, and patterns

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/vx-testing/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# VX Testing Rules

## Test File Location

Tests go in `crates/<name>/tests/` directories — NEVER inline `#[cfg(test)]` modules in source files.

```
crates/vx-resolver/tests/
├── resolver_tests.rs
├── executor_tests.rs
└── spec_tests.rs
```

## Framework

Use `rstest` for parameterized tests:

```rust
use rstest::rstest;

#[rstest]
#[case("node", Ecosystem::NodeJs)]
#[case("npm", Ecosystem::NodeJs)]
#[case("go", Ecosystem::Go)]
fn test_ecosystem_detection(#[case] name: &str, #[case] expected: Ecosystem) {
    let spec = RuntimeSpec::new(name);
    assert_eq!(spec.ecosystem, expected);
}
```

## Naming Convention

```rust
#[test]
fn test_<function_name>_<scenario>() { }

#[tokio::test]
async fn test_<function_name>_<scenario>() { }
```

## Mock Usage

- Mock network calls in unit tests — never use real HTTP
- Use `vx-runtime::testing` mock utilities when available

---
> Source: [loonghao/vx](https://github.com/loonghao/vx) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-06 -->
