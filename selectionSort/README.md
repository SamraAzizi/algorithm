# Selection Sort

This is a C++ program that implements the selection sort algorithm to sort an array of integers.

## Prerequisites

Ensure you have a C++ compiler installed on your system.

## Usage

1. Clone the repository or download the source code files.
2. Open the source code file (`selection_sort.cpp`) in your preferred text editor or IDE.
3. Compile the code using a C++ compiler. For example, you can use `g++`:

    ```bash
    g++ -o selection_sort selection_sort.cpp
    ```

4. Run the compiled executable:

    ```bash
    ./selection_sort
    ```

5. Follow the on-screen instructions to enter 5 integers in any order.
6. The program will display the array before and after sorting using the selection sort algorithm.

## Algorithm

The program uses the following steps to sort the array using the selection sort algorithm:

1. Find the minimum element in the unsorted portion of the array.
2. Swap it with the first unsorted element.
3. Repeat the process for the remaining unsorted portion of the array.

## Example

```plaintext
Enter 5 integers in random order:
5 2 8 1 3
UNSORT ARRAY:
5 2 8 1 3
SORT ARRAY:
1 2 3 5 8
