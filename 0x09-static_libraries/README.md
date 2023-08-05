# Project Title

## Learning Objectives

At the end of this project, you will be able to explain to anyone, without the help of Google:

### General

- What is a static library, how does it work, how to create one, and how to use it.
- Basic usage of ar, ranlib, nm.

## What is a Static Library?

A static library is a collection of precompiled functions and routines that can be linked with your C program during the compilation process. It contains object files (.o files) and is linked directly with the program. The library becomes a part of the executable binary, making it self-contained.

## Creating a Static Library

To create a static library, follow these steps:

1. Write the source code for your library functions (up to 5 functions per file).
2. Compile each function separately into object files using `gcc -c`.
3. Use `ar` to create the static library by bundling the object files together.

## Using a Static Library

To use a static library in your C program, follow these steps:

1. Write a header file (main.h) with the function prototypes for your library functions.
2. Include the header file in your C library source code and the C program where you'll use the library.
3. Compile the C program and link it with your static library using `-l` flag.

## Basic Usage of ar, ranlib, nm

- `ar`: The archive command is used to create, modify, and extract files from archives (static libraries). Commonly used options include `r` (insert files into the archive), `t` (list files in the archive), `x` (extract files from the archive), and `d` (delete files from the archive).
- `ranlib`: This command is used to generate an index for the static library, which helps to speed up linking operations.
- `nm`: The name list command is used to display the symbol table of object files, libraries, or executables. It shows the names and addresses of the symbols defined and used in the file.
