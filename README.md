# Simple Calculator

I forked the repo, and am adding the documentation for the same.

A basic C-language command-line calculator that reads arithmetic operations from a file (`read.txt`) and computes results using modular functions for each operator.

## 📁 Project Structure
```
├── Makefile # Build configuration
├── calc.c # Main program logic
├── operators.c # Definitions of arithmetic operations
├── operators.h # Function declarations for operations
└── read.txt # Input file containing operations
```

## 🧮 Features

- Supports basic arithmetic operations: `+`, `-`, `*`, `/`
- Reads and processes multiple expressions from a text file
- Modular implementation with separate header and source files for operators

## 🛠️ Build & Run

### Using Makefile:
```bash
make
./calc
```
