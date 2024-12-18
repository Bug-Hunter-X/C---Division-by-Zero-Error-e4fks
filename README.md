# C++ Division by Zero Bug
This repository demonstrates a common error in C++: division by zero.  The `bug.cpp` file contains code that attempts to divide an integer by zero, resulting in undefined behavior. The `bugSolution.cpp` file shows how to prevent this error using proper input validation and error handling.

## How to Reproduce
1. Clone this repository.
2. Compile `bug.cpp` using a C++ compiler (e.g., g++).
3. Run the compiled executable. You'll likely see a crash or unexpected output.

## Solution
The solution involves checking if the divisor is zero before performing the division.  This is demonstrated in `bugSolution.cpp`.

## Lessons Learned
- Always validate your inputs to prevent division by zero and other similar errors.
- Use appropriate error handling techniques to gracefully handle exceptional situations.