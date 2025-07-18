# 🛠 Systems Programming Projects — Multi-Language Edition

This repository contains four core **systems-level programming projects**, each implemented in **C**, **C++**, **Rust**, and **Zig**. The projects are designed to explore key low-level computing concepts such as memory management, process control, data-oriented design, and hardware-efficient computation.

---

## 📚 Projects Overview

| Project Name        | Description                                                                                 | Concepts Covered                      |
|---------------------|---------------------------------------------------------------------------------------------|----------------------------------------|
| **Maze Solver**     | Pathfinding through text-based mazes using BFS or DFS.                                      | File I/O, recursion, stack/queue usage |
| **TinyShell**       | A minimalist UNIX shell supporting built-in commands and process control.                   | Fork/exec, pipes, signals, parsing     |
| **Custom Allocator**| A hand-built memory allocator (e.g., bump or free list) for dynamic memory management.      | Memory layout, alignment, malloc/free  |
| **Matrix Normalize**| Cache-efficient normalization of large 2D float matrices (row/column mean/stddev).          | CPU cache, SIMD (opt), perf tuning     |

---

## 🧪 Language Coverage

Each project is implemented in four systems-level languages:

- 🧵 **C** – The foundation of low-level programming.
- 🧱 **C++** – With added abstraction and standard libraries.
- 🦀 **Rust** – For memory safety without garbage collection.
- ⚡ **Zig** – Simplicity, predictability, and manual control.

---

## 📁 Project Structure

```
/systems-course-projects/
│
├── maze-solver/
│   ├── c/
│   ├── cpp/
│   ├── rust/
│   └── zig/
│
├── tiny-shell/
│   ├── c/
│   ├── cpp/
│   ├── rust/
│   └── zig/
│
├── custom-allocator/
│   ├── c/
│   ├── cpp/
│   ├── rust/
│   └── zig/
│
├── matrix-normalization/
│   ├── c/
│   ├── cpp/
│   ├── rust/
│   └── zig/
```

Each subfolder contains its own `README.md` with:
- Problem statement
- Compilation instructions
- Usage examples
- Performance notes

---

## 🧭 Goals

- Compare **language ergonomics** for low-level tasks.
- Benchmark **runtime and memory performance** across implementations.
- Explore trade-offs in **safety, control, and expressiveness**.

---

## 🔧 Prerequisites

To build all projects:

- **C/C++**: `gcc`, `clang`, or `g++`
- **Rust**: `rustup`, `cargo`
- **Zig**: `zig` >= 0.12.0

Install all via your package manager or from their official sites.

---

## 🧪 Example: Build & Run (Maze Solver in Rust)

```sh
cd maze-solver/rust
cargo build --release
./target/release/maze_solver ./mazes/maze1.txt
```

---

## 📊 Performance Benchmarks

Benchmarks will be tracked and compared in the [`benchmarks.md`](./benchmarks.md) file, including:

- Execution time
- Memory usage
- Binary size

---

## 📜 License

MIT License © 2025 Brendan Cron  
Use, study, modify, and share freely.

---

## 🙋‍♂️ About

This project is part of a self-guided **systems programming curriculum**, inspired by top university courses and modern systems languages.

Feel free to fork, adapt, or contribute!
