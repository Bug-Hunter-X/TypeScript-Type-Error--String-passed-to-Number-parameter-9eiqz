# TypeScript Type Error: String passed to Number parameter

This repository demonstrates a common TypeScript error where a string is passed to a function expecting a number.  This leads to a type error during compilation.

## Bug
The `bug.ts` file contains a function that adds two numbers.  However, it's called with a string and a number, resulting in a type error.

## Solution
The `bugSolution.ts` file corrects the error by ensuring both function arguments are of type number.