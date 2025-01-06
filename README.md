# ArrayIndexOutOfBoundsException Bug in Java

This repository demonstrates a common Java bug: the `ArrayIndexOutOfBoundsException`.  The bug occurs when the program attempts to access an array element using an index that is either negative or greater than or equal to the array's length.

## Bug Description
The `bug.java` file contains code that attempts to access an element at an index that is outside the valid range of the array, leading to the exception.  The solution is shown in `bugSolution.java`.

## How to Reproduce
1. Clone the repository.
2. Compile `bug.java` using a Java compiler (like `javac`).
3. Run the compiled code using the Java Virtual Machine (like `java`).
4. Observe the `ArrayIndexOutOfBoundsException`.