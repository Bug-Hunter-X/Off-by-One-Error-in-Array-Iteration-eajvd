# Off-by-One Error in Java Array

This repository demonstrates a common off-by-one error in Java when iterating over an array.  The bug causes an `ArrayIndexOutOfBoundsException`. The solution shows how to correct the loop to prevent the error. 

## Bug
The bug is in the `main` method of `MyClass.java`. The `for` loop's condition `i <= arr.length` is incorrect, and leads to accessing an element outside of the array's bounds.