# Hack Recursive Function Stack Overflow

This repository demonstrates a common error in Hack: a stack overflow error caused by unbounded recursion.  The `foo` function calculates the factorial of a number recursively.  If the input number is too large, the recursive calls will exceed the maximum call stack depth, leading to a runtime error.

The solution involves converting the recursive function to an iterative approach, avoiding unbounded recursion and the subsequent stack overflow. This iterative approach utilizes a loop for factorial calculation thereby eliminating the recursive calls.