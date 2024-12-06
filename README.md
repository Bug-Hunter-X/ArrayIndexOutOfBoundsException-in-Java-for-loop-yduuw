# ArrayIndexOutOfBoundsException Bug in Java
This repository demonstrates a common error in Java: an ArrayIndexOutOfBoundsException.  The bug arises from an off-by-one error in a for loop iterating over an array.

## Bug Description
The provided Java code attempts to populate an integer array and print the last element.  However, the loop condition `i <= arr.length` causes an attempt to access an index that is out of bounds.

## Solution
The solution involves correcting the loop condition to `i < arr.length`, preventing the index from exceeding the array's maximum valid index.

## How to reproduce the bug
1. Clone this repository.
2. Compile and run the `bug.java` file using a Java compiler.
3. Observe the `ArrayIndexOutOfBoundsException` being thrown.

## How to fix the bug
1. Replace the incorrect loop condition in `bug.java` with the corrected version shown in `bugSolution.java`.
2. Recompile and run the corrected code to observe the successful execution. 