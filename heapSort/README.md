# Heap Sort

This is a C++ program that implements the heap sort algorithm to sort an array of integers.

## Prerequisites

Ensure you have a C++ compiler installed on your system.

## Usage

1. Clone the repository or download the source code files.
2. Open the source code file (`heap_sort.cpp`) in your preferred text editor or IDE.
3. Compile the code using a C++ compiler. For example, you can use `g++`:

    ```bash
    g++ -o heap_sort heap_sort.cpp
    ```

4. Run the compiled executable:

    ```bash
    ./heap_sort
    ```

5. Follow the on-screen instructions to enter the size of the array and then the integers in any order.
6. The program will display the array before and after sorting using the heap sort algorithm.

## Algorithm

The program uses the following steps to sort the array using the heap sort algorithm:

1. Build a max heap from the input array.
2. Extract the maximum element from the heap and move it to the end of the array.
3. Repeat the process for the remaining elements until the array is sorted.

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
