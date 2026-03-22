# Rust Ecosystem (Cargo)

- Rust ecosystem consists of key tools:
  - `rustc`: Rust compiler (compiles `.rs` files into binaries)
  - `cargo`: Build system and dependency manager
  - `rustup`: Toolchain installer and version manager  
    → https://google.github.io/comprehensive-rust/cargo/rust-ecosystem.html

- Cargo responsibilities:
  - Build and run Rust applications
  - Manage dependencies (via crates.io)
  - Handle project structure and workspaces
  - Provide testing support  
    → https://google.github.io/comprehensive-rust/cargo/rust-ecosystem.html

- Rust release model:
  - New release every ~6 weeks
  - Channels:
    - stable
    - beta
    - nightly  
    → https://google.github.io/comprehensive-rust/cargo/rust-ecosystem.html

- Rust editions:
  - 2015, 2018, 2021, 2024
  - Allow gradual evolution without breaking compatibility  
    → https://google.github.io/comprehensive-rust/cargo/rust-ecosystem.html


# Create a New Rust Project

- Create a new project:
  ```bash
  cargo new hello-rust

# Best Projects to Build to Learn a New Programming Language

Building projects is the best way to move from reading syntax to actually understanding how a new language works. Here is a roadmap of projects to build, structured from beginner to advanced.

| Project | Difficulty | Key Concepts Learned |
| :--- | :--- | :--- |
| **CLI To-Do List** | Beginner | Variables, arrays/lists, loops, basic I/O |
| **Number Guesser** | Beginner | Control flow (`if`/`else`), random numbers |
| **Weather App** | Intermediate | HTTP requests, JSON parsing, error handling |
| **Web Scraper** | Intermediate | String manipulation, regex, external libraries |
| **Chat Server** | Advanced | Concurrency, networking (TCP/sockets), state |
| **REST API** | Advanced | Routing, database connections, architecture |
