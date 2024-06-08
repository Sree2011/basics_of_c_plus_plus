# A BASIC C++ PROGRAM STRUCTURE

Here is a basic c++ helloworld program:

```cpp
#include <iostream>

int main()
{
    std::cout << "Hello World!";
    return 0;
}
```

## The main components

| Component    | Description                                                           |
| :----------- | :-------------------------------------------------------------------- |
| `#include`   | A preprocessor directive, used to include header files in the program |
| `iostream`   | The iostream.h header file, which includes standard input and output  |
| `int main()` | Declaration of the main function: Execution of program starts here    |
| `std`        | The standard namespace                                                |
| `::`         | the scope operator, used to refer to methods of a class or namespace  |
| `cout`       | The standard output stream                                            |
| `<<`         | The insertion operator, inserts a value into a stream                 |
| `endl`       | The endline character                                                 |
| `return 0;`  | The return statement                                                  |
