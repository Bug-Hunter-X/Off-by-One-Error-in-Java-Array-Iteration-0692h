# Off-by-One Error in Java Array Iteration

This repository demonstrates a common off-by-one error in Java when iterating through an array.

The `BuggyArraySum.java` file contains code with an error that causes an `ArrayIndexOutOfBoundsException`.
The `FixedArraySum.java` file provides the corrected code.

## Problem

The original code has a loop condition that goes one element past the end of the array, leading to an index out of bounds exception.

## Solution

The solution corrects the loop condition to ensure that the loop terminates before accessing an invalid index. 