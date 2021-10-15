# Rust (Onboarding)

Cargo is the package manager and build system used by Rust.
It can generate basic project skeleton (like `npm init`):

```
cargo new hello_world
```

Can check your cargo version:

```
cargo --version
```

Cargo creates a `Cargo.toml` file and a src directory with `main.rs` inside

Simple print function:

```rust
fn main() {
    println!("Hello, world!");
}
```

To compile src files in Cargo project:

```
cargo build
```

Then to execute compiled code:

```
cargo run
```

---

Linux/macOS compilation and execution (vanilla Rust use):

```
# compile code
rustc main.rs

# run executable
./main
```

---
