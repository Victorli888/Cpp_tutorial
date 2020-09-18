#cplusplus Chapter 1 Basics of C++

* Computer only understands *Machine Lanaguage*
* Programming directly with *Machine Language* is tedious, thus we have high level languages like C++
* The **Compiler** will take programmer code and translate it to the binary numbers used in *Machine Language*

### Structure of a C++ Program
```c++
// hello world in C++
#include <iostream>
int main()
{
    std::cout << "Hello World!";
}
```
* `/<comment>/` comment line
* `#include ` pre-processor that inserts content from another file
* `<iostream>` file known as **header iostream** that allows input and output operations
* `int main()` declaration of a function
* `{}` Curly braces determines the start and end lines of code in a function
* `std::cout << "";` standard character output (print statement)

```c++
// line comment
/* block comment */
```
* use namespace std to allow the use of **unqualified name** (cout)
```c++
// Using namespace std
#include <iostream>
using namespace std;
int main()
{
    cout << "Hello World";
    cout << "I don't want to use std::cout";
}
```
### Variables and types
```c++
a = 5;
b = 2;
a = a + 1;
result = a - b;
```
### Fundamental Data Types
* Character Types (**A**)
* Numerical Integer Types
* Floating-point Types (**3.14**)
* Boolean type

### Declaration of variables
C++ is a strongly-typed language that requires every varaible to be declared with its type before implementation. (allows the compiler to size the variable in memory)
```cpp
int a;
float mynumber;
```
Variables with the same type can be declared on the same line
```cpp
int a,b,c;
// Is the  same as ...
int a;
int b;
int c;
```
### Initialization of Variables
we can declare variables that have a pre-existing determined value this is known as initialiaztion
* **c-like initialization**, **constructor initialization**, and **uniform initialization
```cpp
int x = 0;
int x (0);
int x {0};

