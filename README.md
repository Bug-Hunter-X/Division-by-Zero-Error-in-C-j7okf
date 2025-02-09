# Division by Zero Bug in C

This repository demonstrates a common error in C programming: division by zero. The `bug.c` file contains code that attempts to divide an integer by zero, leading to undefined behavior and a potential program crash.  The `bugSolution.c` file provides a corrected version that handles potential division by zero exceptions.

**Bug:** The original code directly divides an integer variable by another integer variable which might be zero. This results in undefined behavior and typically causes a program crash.

**Solution:**  The solution involves adding a check to ensure the divisor is not zero before performing the division.  If the divisor is zero, an appropriate error message is printed, or alternative action is taken to prevent the program from crashing.