# minigrep

A small, beginner-friendly command-line tool inspired by grep.

## What this project does

This project searches a file for lines that contain a given query.
It supports:

- case-sensitive search
- case-insensitive search using the `IGNORE_CASE` environment variable

## How to run

From the project root, run:

```bash
cargo run -- "query" poem.txt
```

To make the search case-insensitive, run:

```bash
IGNORE_CASE=1 cargo run -- "query" poem.txt
```

## Example

```bash
cargo run -- "duct" poem.txt
```

## Tests

Run the test suite with:

```bash
cargo test
```
