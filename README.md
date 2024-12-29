# Stack Overflow in Recursive Factorial Function

This repository demonstrates a common error in recursive functions: stack overflow.  The `foo` function calculates the factorial of a number recursively. However, it does not handle negative inputs, leading to infinite recursion and a stack overflow.

The `bug.hack` file contains the buggy code. The `bugSolution.hack` file provides a corrected version with proper error handling.

This example highlights the importance of handling base cases correctly in recursive functions and the need for robust error handling to prevent unexpected behavior.
