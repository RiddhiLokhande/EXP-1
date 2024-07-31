# EXP-1A 
## Aim

- To print HELLO WORLD code in C++ language
- to write a calculator code in C++ language

## Software required-

You need to have a C++ compiler installed on your system. Common options include:

- [Microsoft Visual C++](https://visualstudio.microsoft.com/vs/features/cplusplus/)

## Theory
Printing "Hello, World!" in C++ involves several concepts fundamental to the language. To print "Hello, World!" in C++ programming, just place Hello, World! inside an inverted comma ("") after  cout<<.

### Various Components

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

4. **Return Statement: `return 0;`**
   - The `return` statement terminates the `main` function and returns an integer value to the calling process.
   - `0` is traditionally used to indicate that the program ended successfully.
## Code
```cpp
#include<iostream>
int main(){
   std::cout<<"HELLO WORLD";
    return 0;
}
```
## Output
![image](https://github.com/user-attachments/assets/98d2f4bc-d770-47ba-84a5-7fcd356e4cf6)

## Conclusion
This simple program demonstrates the basic structure and workflow of a C++ program, including the use of headers, the main function, standard output, and the return statement.

