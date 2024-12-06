# Java ArrayIndexOutOfBoundsException Bug

This repository demonstrates a common Java error: the `ArrayIndexOutOfBoundsException`. The bug arises from an off-by-one error in array access within a loop.

The `Bug.java` file contains the erroneous code, while `BugSolution.java` shows the corrected version.

## Bug Description
The `main` method initializes an integer array named `arr` of size 5.  A `for` loop then attempts to populate this array. The loop's condition `i <= arr.length` is incorrect; it should be `i < arr.length`. The faulty condition results in an attempt to access `arr[5]`, which is beyond the array's bounds causing the exception.

## Solution
The solution corrects the loop condition to `i < arr.length`, preventing the out-of-bounds access. 