# C-Day-68-Sum-Divisible-by-3-or-5
# C Day 68 - Sum of Numbers Divisible by 3 or 5

## Description

This program takes multiple numbers from the user and calculates the sum of numbers that are divisible by either 3 or 5.

## Example

```text
Enter how many numbers: 6
Enter number 1: 10
Enter number 2: 12
Enter number 3: 7
Enter number 4: 15
Enter number 5: 20
Enter number 6: 8

Sum of numbers divisible by 3 or 5 = 57
```

## Concepts Used

* `for` loop
* `if` statement
* Modulus operator `%`
* Logical OR operator `||`
* `scanf()`
* Variables
* Addition

## How It Works

1. The user enters how many numbers they want to check.
2. The program takes each number using a `for` loop.
3. `%` checks whether the number is divisible by 3 or 5.
4. The `||` operator means at least one condition must be true.
5. If the condition is true, the number is added to `sum`.
6. Finally, the program displays the total sum.

## Important Condition

```c
if (number % 3 == 0 || number % 5 == 0)
```

This means the number should be divisible by **3 or 5**.

## File Name

`sum_divisible_by_3_or_5.c`

## Goal

The goal of this program is to practice loops, conditions, the modulus operator, logical OR, and calculating a sum based on a condition.
