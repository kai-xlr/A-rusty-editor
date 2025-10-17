# WARP.md

This file provides guidance to WARP (warp.dev) when working with code in this repository.

## Project Overview

Hecto is a text editor written in Rust. The project is currently in early development stage with basic project structure in place.

## Common Commands

### Build & Run
- `cargo build` - Build the project
- `cargo run` - Build and run the application
- `cargo build --release` - Build optimized release version
- `cargo run --release` - Run optimized release version

### Testing
- `cargo test` - Run all tests
- `cargo test <test_name>` - Run specific test by name
- `cargo test --release` - Run tests in release mode
- `cargo test --no-fail-fast` - Run all tests even if some fail

### Development Tools
- `cargo check` - Quick compile check without producing executable
- `cargo clippy` - Run Rust linter for code quality
- `cargo fmt` - Format code according to Rust style guidelines
- `cargo doc` - Generate documentation
- `cargo clean` - Clean build artifacts

## Architecture

### Current Structure
- `src/main.rs` - Entry point with basic "Hello, world!" implementation
- `Cargo.toml` - Project manifest with Rust 2024 edition
- No external dependencies currently

### Expected Development Direction
As a text editor project, the architecture will likely evolve to include:
- Terminal I/O handling modules
- Text buffer management
- File operations
- Command parsing and execution
- Cursor and viewport management
- Syntax highlighting (future)

## Development Environment
- Uses Rust 2024 edition
- No external dependencies currently defined
- Standard Rust project layout with src/ directory