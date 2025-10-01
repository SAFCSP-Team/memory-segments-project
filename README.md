# Identify Memory Segments used to Store Variables
## Objectives
The objective of this project is to apply your understanding of memory management to solve a given problem.

## Problem
After understanding how memory management works, identify which segment each variable in a given program is stored in it.

## Implementation
Consider the following C code snippet

```c
#include <stdio.h>

int globalVar = 100;

void calculate() {
    static int staticVar = 50;
    int localVar;

    localVar = 25;
    printf("In Calculate Function\n");
}

int main() {
    printf("In Main Function\n");
    printf("Global Variable: %d\n", globalVar);
    calculate();
    return 0;
}

```
1. Identify and explain where each variable in the code is stored in memory (e.g., data segment, stack, heap, code segment).
2. Describe the output of the program when it is executed.
3. Explain the difference between global variables, static variables, and local variables in terms of their storage and lifetime.

## Submission 
- Create a new issue with the title “Answer [your-username]” and write your answer.
- Create an issue of your questions if you face any trouble solving the project.
