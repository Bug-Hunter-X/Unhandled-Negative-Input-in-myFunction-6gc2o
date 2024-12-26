# Unhandled Negative Input in MATLAB Function

This repository demonstrates a common error in MATLAB: failure to handle negative input values in a function. The `myFunction.m` file contains a function that does not properly process negative inputs, leading to incorrect results or program crashes.

The `bugSolution.m` file provides a corrected version that addresses the issue.

## How to Reproduce

1.  Clone the repository.
2.  Open `bug.m` in MATLAB.
3.  Call `myFunction` with a negative input. Observe the error.
4.  Open `bugSolution.m` to see the corrected code.

## Solution

The solution involves adding explicit handling for negative input values, either through error checking or by modifying the function's logic to accommodate such inputs.