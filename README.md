# 0x11. C - printf

## Table of Contents
* [Description](#description)
* [Concepts](#concepts)
* [Authorized Functions and Macros](#authorized-functions-and-macros)
* [Compilation](#compilation)
* [Main Header File](#main-header-file)
* [Sample Test](#sample-test)
* [Edge Cases](#edge-cases)
* [Working Together](#working-together)
* [Authors](#authors)

## Description
In this project, we will be implementing a custom version of the `printf` function in C. The `printf` function is used to format and print data to the standard output. Our goal is to understand the inner workings of `printf` and replicate its functionality.

## Concepts
Before starting the project, it is essential to be familiar with the following concepts:
* Group Projects
* Pair Programming - How To
* Flowcharts
* Technical Writing

## Authorized Functions and Macros
The only functions and macros we are allowed to use from the C standard library are:
* `write` (man 2 write)
* `malloc` (man 3 malloc)
* `free` (man 3 free)
* `va_start` (man 3 va_start)
* `va_end` (man 3 va_end)
* `va_copy` (man 3 va_copy)

## Compilation
To compile our code, we need to use the following flags:
```bash
gcc -Wall -Werror -Wextra -pedantic -std=gnu89 *.c
```
Be careful not to push any C file containing a `main` function in the root directory of the project. The `main` function should be placed in a test folder containing all the test files.

## Main Header File
Our main files will include a common header file named `main.h`. This header file should contain all the function prototypes and necessary macros used in the implementation of `printf`.

## Sample Test
Here is an example of a test file that can be used to verify our custom `printf` function:
```c
#include <limits.h>
#include <stdio.h>
#include "main.h"

int main(void)
{
    // Test cases go here
    return (0);
}
```
Remember to include the necessary test cases to cover different formats and edge cases.

## Edge Cases
If the task does not specify what to do with an edge case, we should follow the behavior of the standard `printf` function.

## Working Together
We strongly encourage all team members to collaborate on creating a comprehensive set of tests. This collaborative effort will help ensure that our `printf` implementation covers a wide range of scenarios and produces accurate results.

## Authors
Jonathan Walumbe and Ian Powell.

## Note
This README.md provides an outline for the "0x11. C - printf" project. Feel free to add more sections or modify the content according to the specific requirements and guidelines of your project.
