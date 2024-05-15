# Insertion Sort

This is a simple C++ program that implements the insertion sort algorithm to sort an array of integers.


## Algorithm

The program uses the following steps to sort the array using the insertion sort algorithm:

1. Start from the second element of the array (`i = 1`).
2. Store the current element (`arr[i]`) in a variable `key`.
3. Initialize a variable `j` to `i - 1`.
4. Compare `key` with each element to its left (`arr[j]`) and shift elements to the right until finding the correct position for `key`.
5. Insert `key` at the correct position in the sorted array.
6. Repeat steps 2-5 until all elements are in their correct positions.

## Example

```plaintext
Enter 5 integers in any order:
5 2 8 1 3
Before Sorting:
5 2 8 1 3
After Sorting:
1 2 3 5 8
