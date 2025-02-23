# Principles-of-compilation
# 🛠️ Scheme Compiler in OCaml
This repository contains my implementation of a compiler for Scheme, developed as part of the Compiler Construction course. The project is written in OCaml and includes key components such as lexical analysis, parsing, and code generation.

## 📋 Project Overview
The project consists of two assignments followed by a final project:

| Assignment      | Description |
|----------------|-------------|
| **Assignment 1** | Implement lexical analysis and parsing by replacing `raise (X_not_yet_implemented "hw 1")` with the appropriate functionality. |
| **Assignment 2** | Extend the compiler to handle more complex parsing and compilation tasks, replacing `raise (X_not_yet_implemented "hw 2")`. |
| **Final Project** | Generate x86 assembly code for Scheme programs. This involves writing assembly code and testing it on an x86 machine with Linux ABI compatibility. |

## 📂 File Structure
- **compiler.ml**: Main OCaml file with the compiler’s implementation. Sections are marked for different phases of the project.
- **makefile**: Automates assembling and linking generated assembly files.

## 🧪 Compilation and Testing
The compiler provides functions to compile and execute Scheme code:

- `compile_scheme_string`: Compiles a Scheme expression into an assembly file.
- `compile_and_run_scheme_string`: Compiles, assembles, and executes a Scheme expression for quick testing.

### Example Usage
```ocaml
Code_Generation.compile_and_run_scheme_string "testing/goo" "(+ 2 3)"
```

## ⚠️ Notes
- Ensure unnecessary debug output is removed to avoid incorrect results.
- Frequent testing helps in debugging and refining the compiler.

## 📦 Requirements
- **OCaml**: Required for implementation.
- **NASM**: Needed for assembling the generated assembly code.
- **Linux ABI**: Code generation is designed for Linux ABI, so testing requires an x86-compatible environment.

## 👨‍💻 Author
This compiler was implemented as part of my Compiler Construction course project, following guidelines provided by Mayer Goldberg.
