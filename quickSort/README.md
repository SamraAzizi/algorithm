# Quick Sort

This is a C++ program that implements the quick sort algorithm to sort an array of integers.

## Prerequisites

Ensure you have a C++ compiler installed on your system.

## Usage

1. Clone the repository or download the source code files.
2. Open the source code file (`quick_sort.cpp`) in your preferred text editor or IDE.
3. Compile the code using a C++ compiler. For example, you can use `g++`:

    ```bash
    g++ -o quick_sort quick_sort.cpp
    ```

4. Run the compiled executable:

    ```bash
    ./quick_sort
    ```

5. Follow the on-screen instructions to enter the size of the array and then the integers in any order.
6. The program will display the array before and after sorting using the quick sort algorithm.

## Algorithm

The program uses the following steps to sort the array using the quick sort algorithm:

1. Select a pivot element from the array (usually the last element).
2. Partition the array into two sub-arrays such that elements less than the pivot are on the left, and elements greater than or equal to the pivot are on the right.
3. Recursively apply quick sort to the left and right sub-arrays.

## Example

```plaintext
Enter size of Array:
5
Enter 5 integers in any order:
5 2 8 1 3
Before Sorting:
5 2 8 1 3
After Sorting:
1 2 3 5 8
