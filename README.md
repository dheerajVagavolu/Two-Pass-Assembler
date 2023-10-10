# 2-Pass Assembler in C++

## Overview

This project is a simple implementation of a 2-pass assembler in C++. The assembler takes assembly language source code as input and produces the corresponding machine code. The two-pass process ensures that all symbols (like labels) are correctly resolved, even if they are used before they are defined.

## Features

1. **First Pass**: Scans the source code to build the symbol table, which maps labels to their corresponding memory addresses.
2. **Second Pass**: Translates the assembly instructions into machine code, using the symbol table to resolve any labels.

## Prerequisites

- A C++ compiler (e.g., GCC, Clang)
- Basic knowledge of assembly language and machine code

## How to Compile and Run

1. Navigate to the project directory.
2. Compile the assembler
3. Run the assembler with an input assembly file
