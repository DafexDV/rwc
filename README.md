# rwc

A small Rust CLI that recreates the basic functionality of the Linux `wc` command.

## Installation

### Prerequisites

Make sure you have [Rust](https://www.rust-lang.org/) and Cargo installed.

### Clone the repository

```bash
git clone https://github.com/DafexDV/rwc.git
cd rwc
```

### Run

You can run the program directly with Cargo:

```bash
cargo run -- <FILES>
```

For example:

```bash
cargo run -- Cargo.toml Cargo.lock
```

## Usage

```bash
rwc <FILES>
```

For example:

```bash
rwc Cargo.toml Cargo.lock
```

## Build

To create an optimized release binary:

```bash
cargo build --release
```

The binary will be available at:

```text
target/release/rwc
```

## License

This project is licensed under the MIT License.
