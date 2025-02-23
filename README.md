# Scheme Compiler in OCaml 🚀

This repository contains my implementation of a Scheme compiler, built as part of the Compiler Construction course. The compiler is written in OCaml and generates x86 assembly code compatible with the Linux ABI.

## Features 🛠️
- **Lexical Analysis**: Tokenizing Scheme source code.
- **Parsing**: Transforming code into an abstract syntax tree (AST).
- **Code Generation**: Producing x86 assembly code.

## Getting Started 🚀
### Prerequisites
Ensure you have the following installed:
- **OCaml** (for development and execution)
- **NASM** (for assembling the generated assembly code)
- **Linux ABI-compatible environment**

### Installation
Clone the repository and navigate into the project folder:
```sh
git clone https://github.com/yourusername/scheme-compiler.git
cd scheme-compiler
make
```

### Usage
To compile and run a Scheme expression:
```ocaml
Code_Generation.compile_and_run_scheme_string "(+ 5 7)"
```

## Development Notes ⚠️
- Debugging outputs should be removed before final execution.
- Regular testing ensures compiler correctness.

## Author 👨‍💻
Developed as part of my Compiler Construction coursework under the guidance of Mayer Goldberg.

## License 📜
This project is for educational purposes. Contributions and forks are welcome!
