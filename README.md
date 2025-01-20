# Julia Function Bug
This repository demonstrates a bug in a simple Julia function that calculates the square of a number. The function exhibits unexpected behavior when given a negative input. The bug and its solution are provided in separate files.

## Bug Description
The `myfunction` function intends to return the square of the input, handling zero and negative inputs separately. However, due to a flaw in the logic, it returns the negative square of negative inputs.

## Solution
The solution file (`bugSolution.jl`) demonstrates the corrected version of the function.