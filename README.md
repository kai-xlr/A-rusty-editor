# Hecto

A text editor written in Rust, inspired by the classic tutorial "Build Your Own Text Editor" but implemented with modern Rust practices.

## Features

- [x] Basic project structure
- [ ] Terminal raw mode handling
- [ ] Text buffer management
- [ ] File I/O operations
- [ ] Cursor movement and positioning
- [ ] Text editing capabilities
- [ ] Search functionality
- [ ] Syntax highlighting

## Getting Started

### Prerequisites

- Rust 1.70+ (using 2024 edition)
- Cargo package manager

### Building and Running

```bash
# Build the project
cargo build

# Run the editor
cargo run

# Build optimized release version
cargo build --release
```

### Development

```bash
# Run tests
cargo test

# Check code without building
cargo check

# Format code
cargo fmt

# Run linter
cargo clippy
```

## Project Structure

```
hecto/
├── src/
│   └── main.rs          # Main entry point
├── Cargo.toml           # Project manifest
├── Cargo.lock           # Dependency lock file
└── README.md            # This file
```

## Contributing

This is a learning project. Feel free to experiment with the code and suggest improvements.

## License

This project is open source and available under the MIT License.
