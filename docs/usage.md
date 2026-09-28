# Usage

The README covers the basics. This page collects the
longer examples and the notes that did not fit up front.

## Basic

```bash
./target/release/linely src/*.rs
cat README.md | ./target/release/linely
```

## Notes

- Parallel over files with std threads
- Zero dependencies outside std
