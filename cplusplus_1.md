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