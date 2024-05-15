# Merge Sort

This is a C++ program that implements the merge sort algorithm to sort an array of integers.

## Prerequisites

Ensure you have a C++ compiler installed on your system.

## Usage

1. Clone the repository or download the source code files.
2. Open the source code file (`merge_sort.cpp`) in your preferred text editor or IDE.
3. Compile the code using a C++ compiler. For example, you can use `g++`:

    ```bash
    g++ -o merge_sort merge_sort.cpp
    ```

4. Run the compiled executable:

    ```bash
    ./merge_sort
    ```

5. Follow the on-screen instructions to enter 5 integers in any order.
6. The program will display the array before and after sorting using the merge sort algorithm.

## Algorithm

The program uses the following steps to sort the array using the merge sort algorithm:

1. Divide the array into two halves recursively until each sub-array contains only one element.
2. Merge the two sorted halves into a single sorted array.

## Example

```plaintext
Enter 5 integers in any order:
5 2 8 1 3
Before Sorting:
5 2 8 1 3
After Sorting:
1 2 3 5 8
