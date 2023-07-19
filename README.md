# Learning Objectives

At the end of this project, you are expected to be able to explain to anyone, without the help of Google:

## General

- Why C programming is awesome
- Who invented C
- Who are Dennis Ritchie, Brian Kernighan, and Linus Torvalds
- What happens when you type `gcc main.c`
- What is an entry point
- What is main
- How to print text using `printf`, `puts`, and `putchar`
- How to get the size of a specific type using the unary operator `sizeof`
- How to compile using GCC
- What is the default program name when compiling with GCC
- What is the official C coding style and how to check your code with `betty-style`
- How to find the right header to include in your source code when using a standard library function
- How does the main function influence the return value of the program

## Why C programming is awesome

C is a powerful and versatile programming language that has been widely used in various fields for decades. It allows for low-level memory manipulation and direct hardware access, making it suitable for system programming and embedded systems. C is known for its efficiency and performance, making it a popular choice for developing operating systems, compilers, and other performance-critical applications. It also serves as the foundation for many other programming languages.

## Who invented C

C programming language was invented by Dennis Ritchie in the early 1970s while working at Bell Labs. He designed C as an evolution of the B programming language (an earlier system programming language). Dennis Ritchie is often referred to as the "father of C."

## Who are Dennis Ritchie, Brian Kernighan, and Linus Torvalds

- Dennis Ritchie: Inventor of the C programming language and a significant contributor to the development of Unix operating system.
- Brian Kernighan: A computer scientist known for co-authoring "The C Programming Language" with Dennis Ritchie, a highly influential programming book.
- Linus Torvalds: A renowned software engineer who created the Linux kernel, predominantly written in C, showcasing the continued relevance of C in modern computing.

## What happens when you type `gcc main.c`

When you type `gcc main.c` in the command line, it invokes the GNU Compiler Collection (GCC) to compile the C source file named `main.c`. The compilation process involves several stages, such as preprocessing, compilation, assembly, and linking, which ultimately results in generating an executable binary file.

## What is an entry point

In C programming, an "entry point" refers to the starting point of a program's execution. When you run a C program, the operating system needs to know where to begin executing the code. The standard entry point in a C program is the `main()` function.

## What is main

`main()` is a special function in C programming that serves as the entry point for the program's execution. It is mandatory in every C program, and the program's execution begins from the first statement inside the `main()` function. The `main()` function can have a return type of `int` to indicate the exit status of the program.

## How to print text using `printf`, `puts`, and `putchar`

- `printf`: The `printf()` function is used to print formatted text to the standard output (usually the console). It allows you to print variables, strings, and other data types with specified formats.

```c
#include <stdio.h>

int main() {
    int age = 25;
    printf("My age is %d years.\n", age);
    return 0;
}
