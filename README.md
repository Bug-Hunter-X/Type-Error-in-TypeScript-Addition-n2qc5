# Type Error in TypeScript Addition

This repository demonstrates a common type error in TypeScript that arises when performing arithmetic operations with mismatched types. The `add` function is designed to accept two numbers and return their sum. However, the example call attempts to add a number and a string, which is not type-safe. This leads to a compilation error, preventing the potentially problematic code from running.

The solution demonstrates how to address the issue through type checking and appropriate type casting. The improved version of the `add` function handles potential type mismatches, ensuring that only numbers are used in the addition operation.