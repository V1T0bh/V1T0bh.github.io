---
title: Topic 2 - Control Flow and Conditionals
layout: page
---

## Introduction

Control flow statements allow you to control the execution path of your program.

## If-Else Statements

### Basic If Statement
```c
int score = 85;

if (score >= 90) {
    printf("Grade A\n");
} else if (score >= 80) {
    printf("Grade B\n");
} else if (score >= 70) {
    printf("Grade C\n");
} else {
    printf("Grade F\n");
}
```

## Switch Statements

```c
int day = 3;

switch(day) {
    case 1:
        printf("Monday\n");
        break;
    case 2:
        printf("Tuesday\n");
        break;
    case 3:
        printf("Wednesday\n");
        break;
    default:
        printf("Invalid day\n");
}
```

## Loops

### For Loop
```c
for (int i = 0; i < 5; i++) {
    printf("%d ", i);
}
// Output: 0 1 2 3 4
```

### While Loop
```c
int count = 0;
while (count < 5) {
    printf("%d ", count);
    count++;
}
```

### Do-While Loop
```c
int num = 0;
do {
    printf("%d ", num);
    num++;
} while (num < 5);
```

## Logical Operators

- `&&` - AND operator
- `||` - OR operator
- `!` - NOT operator

### Example
```c
int age = 20;
bool hasLicense = true;

if (age >= 18 && hasLicense) {
    printf("Can drive!\n");
}
```

## Practice Problems

1. Write a program to check if a number is even or odd
2. Create a calculator using switch statements
3. Print numbers 1-100 using different loop types
4. Find the largest of three numbers

## Important Notes
- Always use `break` in switch cases (unless fall-through is intended)
- Be careful with infinite loops
- Use proper indentation for readability

---

[← Back to CS1010](../)
