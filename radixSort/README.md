# Radix Sort

This is a C++ program that implements the radix sort algorithm to sort an array of integers.


## Algorithm

The program uses the following steps to sort the array using the radix sort algorithm:

1. Find the maximum element in the array to determine the number of digits in the maximum number.
2. Perform counting sort for each digit (from the least significant digit to the most significant digit).
3. After sorting all digits, the array will be sorted.

## Example

```plaintext
Enter the size of the array:
5
Enter 5 integers in any order:
5 2 8 1 3
Before Sorting:
5 2 8 1 3
After Sorting:
1 2 3 5 8
