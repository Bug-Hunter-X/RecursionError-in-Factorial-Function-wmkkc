# RecursionError in Factorial Function

This repository demonstrates a common error in Python involving recursion:  a missing or incomplete base case in a recursive function. The provided `factorial` function correctly calculates factorials for non-negative integers.  However, if a negative number is passed as an argument, the function will recursively call itself indefinitely until a `RecursionError` occurs, causing the program to crash.

The `bugSolution.py` file shows how to correct this error by adding proper error handling or by adding a condition for when the input is negative. 