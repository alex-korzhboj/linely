# linely

Fast line/byte counter written in Rust

## Examples

```bash
./target/release/linely src/*.rs
cat README.md | ./target/release/linely
```

## What it does

- Zero dependencies outside std
- Parallel over files with std threads
- Reads stdin or multiple files
- Counts lines, words and bytes like wc

## Getting started

```bash
cargo build --release
```

## Project structure

```text
├── .github/
│   └── workflows/
│       └── ci.yml
├── docs/
│   ├── configuration.md
│   ├── development.md
│   ├── roadmap.md
│   └── usage.md
├── examples/
│   └── quickstart.md
├── src/
│   └── main.rs
├── .gitattributes
├── .gitignore
├── CHANGELOG.md
├── Cargo.toml
├── LICENSE
└── SECURITY.md
```

## Development

```bash
cargo build
cargo clippy -- -D warnings
```

## License

MIT. Do whatever you want.
