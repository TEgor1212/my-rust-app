# my-rust-app

![CI](https://github.com/TEgor1212/my-rust-app/actions/workflows/ci.yml/badge.svg)

Rust app with CI — `cargo build` + `cargo test` on push and PR.

A simple Rust application with a CI pipeline that checks formatting with `rustfmt`, lints with Clippy, and runs `cargo build` + `cargo test` (debug and release modes). A Docker image is built and tested on success.

## Quick Start

```bash
cargo check
cargo build
cargo test
```