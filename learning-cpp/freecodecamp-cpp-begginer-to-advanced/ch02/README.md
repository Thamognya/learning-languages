# Notes

Notes from 1:43:01 to 3:00:47, ch02

## Hello world

Check [helloworld.cpp](./hello-world/helloworld.cpp)

## Compiler errors

### compile time errors

Errors that occur at compile time. Like missing semicolons, missing closing brackets, and etc. You have to fix the error before compiling again.

see [compile.cpp](./errors/compile.cpp)

### run time errors

Errors that occur at run time. They can compile properly, but can not run properly. You have to fix the error, recompile and then run again. They can cause the problem to crash.

see [runtime.cpp](./errors/runtime.cpp)

### warnings

Errors that are not enough to stop the compiler from compiling, but are enough to stop the program to run (under some circumstances).

see [warning.cpp](./errors/warning.cpp)

## statements

- statement is a basic unit of computation in a c++ program
- every c++ program is made up of statements
- statements are executed in order
- statements end with a semicolons
- executions continues until there is a statement to terminate or another sequence of statements to execute
- smallest thing the cpu can execute in your program

see [statement.cpp](./statements/statement.cpp)

## Function

- takes input or parameters and returns an output based on some operations

sum function which adds the 2 inputs and gives an sum output:

```
first number ->

                    [function] -> sum 
                    
second number ->
```

see [sumfunction.cpp](./function/sumfunction.cpp)

function syntax

```c++
int addNumbers(int a, int b) {
    int sum = a + b;
    return sum;
}
```

int is the return type

addNumbers is the function name

int a, int b are the parameters

then curly braces, and inside it the function body

int sum is the function command

and return sum, returns the sum


- a function must defined before it is use

