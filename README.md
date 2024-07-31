# EXP-1
# Hello World in C++

This repository contains a simple "Hello, World!" program written in C++.

## Getting Started

These instructions will help you set up and run the program on your local machine.

### Software required-

You need to have a C++ compiler installed on your system. Common options include:

- [Microsoft Visual C++](https://visualstudio.microsoft.com/vs/features/cplusplus/)

### Theory-
Printing "Hello, World!" in C++ involves several concepts fundamental to the language. Here's a breakdown of the theory behind each part of the typical "Hello, World!" program in C++:

```cpp
#include <iostream>

int main() {
    std::cout << "Hello, World!" << std::endl;
    return 0;
}
```

### Explanation of Each Component

1. **Preprocessor Directive: `#include <iostream>`**
   - The `#include` directive tells the preprocessor to include the contents of the `iostream` header file.
   - `iostream` stands for input-output stream and provides functionalities for input and output operations.
   - Specifically, it includes definitions for objects like `std::cin`, `std::cout`, `std::cerr`, and more.

2. **Main Function: `int main()`**
   - The `main` function is the entry point of every C++ program. When the program is executed, the execution starts from the `main` function.
   - `int` before `main` indicates that the function returns an integer value.

3. **Output Statement: `std::cout << "Hello, World!" << std::endl;`**
   - `std::cout` is an object of the `ostream` class defined in the `iostream` header. It is used to output data to the standard output, usually the screen.
   - The `<<` operator is called the insertion operator. It is used to send data to the output stream.
   - `"Hello, World!"` is a string literal that is passed to `std::cout` for output.
   - `std::endl` is an output manipulator that inserts a newline character and flushes the output buffer, ensuring that the output is displayed immediately.

4. **Return Statement: `return 0;`**
   - The `return` statement terminates the `main` function and returns an integer value to the calling process.
   - `0` is traditionally used to indicate that the program ended successfully.

### Steps in Execution

1. **Preprocessing:**
   - The preprocessor processes the `#include <iostream>` directive and includes the contents of the `iostream` header file.

2. **Compilation:**
   - The C++ compiler compiles the source code into an object file, translating the high-level C++ code into machine code.

3. **Linking:**
   - The linker links the object file with necessary libraries (like the standard C++ library) to produce an executable file.

4. **Execution:**
   - When the executable file runs, the operating system calls the `main` function.
   - The `main` function executes, sending the "Hello, World!" string to `std::cout`, which displays it on the screen.
   - The program returns 0 to the operating system, indicating successful execution.

This simple program demonstrates the basic structure and workflow of a C++ program, including the use of headers, the main function, standard output, and the return statement.

1. Clone this repository to your local machine:
    ```sh
    git clone https://github.com/your-username/hello-world-cpp.git
    cd hello-world-cpp
    ```

2. Compile the program:
    ```sh
    g++ hello.cpp -o hello
    ```

3. Run the executable:
    ```sh
    ./hello
    ```

You should see the following output:
