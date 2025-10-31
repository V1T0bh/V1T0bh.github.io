---
title: Topic 1 - Introduction to C Programming
layout: page
---

## Introduction

This topic covers the basics of C programming including...

## Key Concepts

### Variables and Data Types
- `int` - Integer type
- `float` - Floating point numbers
- `char` - Character type
- `double` - Double precision floating point

### Basic Syntax
```c
#include <stdio.h>

int main() {
    printf("Hello, World!\n");
    return 0;
}
```

## Examples

### Example 1: Simple Variable Declaration
```c
int age = 21;
float gpa = 4.5;
char grade = 'A';
```

### Example 2: Basic Input/Output
```c
int number;
printf("Enter a number: ");
scanf("%d", &number);
printf("You entered: %d\n", number);
```

## Practice Problems

1. Write a program that prints your name
2. Create variables for different data types
3. Take user input and display it

## Notes
- Remember to include `stdio.h` for input/output
- Always return 0 from main()
- Use `&` operator with scanf for variables

---

[← Back to CS1010](../)
