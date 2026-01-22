# echo-rs

A Rust implementation of the Unix `echo` command.

## Description

`echo-rs` is a simple command-line utility that prints text to the standard output. It mimics the behavior of the standard `echo` command found on Unix-like systems.

## Building

To build the project:

```bash
cargo build --release
```

The compiled binary will be located at `target/release/echo-rs`.

## Usage

```bash
echo-rs [FLAGS] <TEXT>...
```

### Arguments

- `<TEXT>...` - The text to print (one or more arguments)

### Flags

- `-n` - Do not print a trailing newline

### Examples

Print a simple message:
```bash
echo-rs "Hello, World!"
```

Print multiple arguments:
```bash
echo-rs Hello World
```

Print without a trailing newline:
```bash
echo-rs -n "No newline"
```

## Testing

Run the test suite:

```bash
cargo test
```

## Author

arur17

## Version

0.1.0
