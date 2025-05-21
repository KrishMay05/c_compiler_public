If you’d like to see the source or contribute, please [request collaborator access](https://github.com/KrishMay05/C_compiler).

# 🔧 C Compiler Project

A custom C compiler built using **Flex (Lex)** and **Bison (Yacc)** that performs lexical analysis, parsing, and code generation for a subset of the C programming language. The compiler outputs **x86-64 assembly code**, ready to be assembled and linked using `gcc`.

## 📚 Features

- ✅ Lexical analysis using **Flex**
- ✅ Syntax parsing with **Bison**
- ✅ Assembly code generation (target: `x86-64`)
- ✅ Support for:
  - Variable declarations and assignments
  - Arithmetic and logical expressions
  - Control flow: `if`, `if-else`, `while`, `for`
  - Block-level scoping
  - Function definitions and calls
  - Print and return statements

## 🛠 Technologies Used

- **C**
- **Flex** – for tokenizing source code
- **Bison** – for parsing and grammar rule enforcement
- **NASM/GCC** – for assembling and linking generated code

## 📁 Project Structure

├── Makefile # Automates build process
├── compiler.l # Flex file (tokenizer)
├── compiler.y # Bison file (parser)
├── ast.c/.h # Abstract Syntax Tree logic
├── symtab.c/.h # Symbol table management
├── codegen.c/.h # Assembly code generation
├── test.c # Sample test input
└── README.md # You are here

