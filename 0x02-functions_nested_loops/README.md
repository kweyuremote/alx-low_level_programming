# Learning Objectives

At the end of this project, you are expected to be able to explain to anyone, without the help of Google:

## General

- What are nested loops and how to use them
- What is a function and how do you use functions
- What is the difference between a declaration and a definition of a function
- What is a prototype
- Scope of variables
- What are the gcc flags -Wall -Werror -pedantic -Wextra -std=gnu89
- What are header files and how to use them with #include

## Requirements

### General

- Allowed editors: vi, vim, emacs
- All your files will be compiled on Ubuntu 20.04 LTS using gcc, using the options -Wall -Werror -Wextra -pedantic -std=gnu89
- All your files should end with a new line
- A README.md file, at the root of the folder of the project is mandatory
- Your code should use the Betty style. It will be checked using betty-style.pl and betty-doc.pl
- You are not allowed to use global variables
- No more than 5 functions per file
- You are not allowed to use the standard library. Any use of functions like printf, puts, etc… is forbidden
- You are allowed to use _putchar
- You don’t have to push _putchar.c, we will use our file. If you do it won’t be taken into account
- In the following examples, the main.c files are shown as examples. You can use them to test your functions, but you don’t have to push them to your repo (if you do we won’t take them into account). We will use our own main.c files at compilation. Our main.c files might be different from the one shown in the examples
- The prototypes of all your functions and the prototype of the function _putchar should be included in your header file called main.h
- Don’t forget to push your header file

##answers
I apologize for the confusion. Here's the complete content in Markdown format for the GitHub README.md:

```markdown
# Learning Objectives

At the end of this project, you are expected to be able to explain to anyone, without the help of Google:

## General

- **What are nested loops and how to use them**

   Nested loops are loops within loops. They allow you to repeat a set of statements multiple times, and within each iteration of the outer loop, the inner loop executes its own set of statements multiple times. This is useful for performing tasks that require multiple iterations, such as traversing two-dimensional arrays or generating certain patterns.

- **What is a function and how do you use functions**

   A function is a self-contained block of code that performs a specific task. It allows you to break down your code into smaller, manageable pieces, making it more organized and easier to maintain. Functions are declared with a return type, a name, and can have parameters (input) and a return value (output).

- **What is the difference between a declaration and a definition of a function**

   A function declaration tells the compiler about the existence of a function, providing its name, return type, and parameters. It does not contain the actual implementation of the function.

   A function definition, on the other hand, provides the actual implementation of the function, including its body with the statements that perform the task.

- **What is a prototype**

   A prototype is a function declaration that provides information about the function's name, return type, and parameters. It acts as a forward declaration, allowing the compiler to know about the existence of a function before its actual definition.

- **Scope of variables**

   The scope of a variable refers to the part of the program where the variable is accessible. Variables declared inside a function have local scope, meaning they are only accessible within that function. Variables declared outside of any function, typically at the beginning of a file, have global scope and are accessible throughout the entire program.

- **What are the gcc flags -Wall -Werror -pedantic -Wextra -std=gnu89**

   - `-Wall`: Enables all the warning messages during compilation, helping to catch potential issues in the code.
   - `-Werror`: Treats all warning messages as errors, halting the compilation if any warnings are present.
   - `-pedantic`: Enforces strict ISO C standards compliance.
   - `-Wextra`: Enables additional warning messages, providing extra checks for potential problems.
   - `-std=gnu89`: Specifies the C language standard to use, in this case, GNU C89.

- **What are header files and how to use them with #include**

   Header files contain function prototypes, macro definitions, and type declarations that are shared across multiple source files. They allow you to declare functions in one file and define them in another, providing modularity to the code. The `#include` preprocessor directive is used to include header files in a C program.

## Requirements

- **General**

   - Allowed editors: vi, vim, emacs
   - All your files will be compiled on Ubuntu 20.04 LTS using gcc, using the options -Wall -Werror -Wextra -pedantic -std=gnu89
   - All your files should end with a new line
   - A README.md file, at the root of the folder of the project is mandatory
   - Your code should use the Betty style. It will be checked using betty-style.pl and betty-doc.pl
   - You are not allowed to use global variables
   - No more than 5 functions per file
   - You are not allowed to use the standard library. Any use of functions like printf, puts, etc… is forbidden
   - You are allowed to use _putchar
   - You don’t have to push _putchar.c, we will use our file. If you do it won’t be taken into account
   - In the following examples, the main.c files are shown as examples. You can use them to test your functions, but you don’t have to push them to your repo (if you do we won’t take them into account). We will use our own main.c files at compilation. Our main.c files might be different from the one shown in the examples
   - The prototypes of all your functions and the prototype of the function _putchar should be included in your header file called main.h
   - Don’t forget to push your header file
```

This Markdown content includes the learning objectives and requirements for the project, formatted for the GitHub README.md file. Please use this as a reference or starting point for your project's README.md and add any additional information or examples as needed.