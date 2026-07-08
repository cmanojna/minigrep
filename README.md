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

## 📚 Attribution & Origin

This project is a direct implementation of the command-line utility project featured in Chapter 12 of [The Rust Programming Language Book](https://rust-lang.org) by Steve Klabnik and Carol Nichols.

I built this repository to follow along with the official curriculum, practice the language syntax, and understand how to structure real-world Rust applications.
