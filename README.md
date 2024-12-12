# Off-by-one Error in Array Iteration

This example demonstrates a common off-by-one error in Java when iterating over arrays. The error occurs because the loop condition `i <= arr.length` tries to access an index that is out of bounds.  Arrays in Java are zero-indexed, meaning the valid indices are from 0 to `arr.length - 1`.

The `Bug.java` file contains the code with the error.  The `BugSolution.java` file provides the corrected code.