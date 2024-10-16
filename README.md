# Low Level Programming in C

This repository contains implementations of fundamental C programming concepts and algorithms, progressing from basic syntax to advanced topics.

## Modules

### **hello_world**
- Compilation stages (preprocessor, compiler, assembler, linker)
- Basic C program structure and output functions
- Understanding the build process

### **variables_if_else_while**
- Variable declarations and initialization
- Conditional statements and logical operators
- Loop constructs (while, for)
- Character and number manipulation

### **functions_nested_loops**
- Function declarations and definitions
- Parameter passing and return values
- Nested loop patterns and algorithms
- Mathematical computations and number theory

### **pointers_arrays_strings**
- Pointer arithmetic and dereferencing
- Array manipulation and traversal
- String operations and memory handling
- Character array processing

### **recursion**
- Recursive function design patterns
- Base cases and recursive calls
- Mathematical algorithms (factorial, power, sqrt)
- String processing with recursion

### **malloc_free**
- Dynamic memory allocation
- Memory management best practices
- 2D array creation and cleanup
- String duplication and concatenation

### **structures_typedef**
- Custom data type definitions
- Structure initialization and access
- Memory allocation for structures
- Data encapsulation patterns

### **function_pointers**
- Function pointer declarations and usage
- Callback mechanisms
- Function arrays and dispatch tables
- Calculator implementation with function pointers

### **file_io**
- File reading and writing operations
- System call interfaces
- File descriptor management
- Binary file processing (ELF headers)

## Usage

Each module contains its own README with specific instructions. Compile individual programs with:

```bash
gcc -Wall -Werror -Wextra -pedantic filename.c -o output
```

## Learning Path

The modules are designed to be studied in order, building upon concepts from previous sections:

1. Basic syntax and compilation → **hello_world**
2. Control structures → **variables_if_else_while** 
3. Functions and algorithms → **functions_nested_loops**
4. Memory and pointers → **pointers_arrays_strings**
5. Advanced algorithms → **recursion**
6. Dynamic memory → **malloc_free**
7. Data structures → **structures_typedef**
8. Advanced pointers → **function_pointers**
9. System programming → **file_io**