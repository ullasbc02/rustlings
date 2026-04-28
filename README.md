# [Rustlings](https://rustlings.rust-lang.org) 🦀

Small exercises to get you used to reading and writing [Rust](https://www.rust-lang.org) code - _Recommended in parallel to reading [the official Rust book](https://doc.rust-lang.org/book) 📚️_

Visit the **website** for a demo, info about setup and more:

## ➡️ [rustlings.rust-lang.org](https://rustlings.rust-lang.org) ⬅️

## Run Exercises In This Repository

Use these commands from the repository root (the folder that contains `Cargo.toml` and `exercises/`).

### 1) Go to the project root

```bash
cd /Users/ullasbc/Documents/Projects/rustlings
```

### 2) Run one specific exercise

```bash
cargo run -- run intro1
```

Replace `intro1` with any exercise name, for example:

```bash
cargo run -- run variables1
cargo run -- run functions3
cargo run -- run if2
```

### 3) Run the next pending exercise

```bash
cargo run -- run
```

### 4) Check all exercises

```bash
cargo run -- check-all
```

### 5) Show a hint

```bash
cargo run -- hint intro1
```

Or hint for the next pending exercise:

```bash
cargo run -- hint
```

### 6) Reset an exercise

```bash
cargo run -- reset intro1
```

### 7) Interactive watch mode

```bash
cargo run
```

## Common mistake

Do not run these commands from inside `exercises/00_intro` (or other exercise subdirectories).
Always run from the repository root.
