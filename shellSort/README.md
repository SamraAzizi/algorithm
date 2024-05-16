# Shell Sort

This is a C++ program that implements the shell sort algorithm to sort an array of integers.

## Prerequisites

Ensure you have a C++ compiler installed on your system.

## Usage

1. Clone the repository or download the source code files.
2. Open the source code file (`shell_sort.cpp`) in your preferred text editor or IDE.
3. Compile the code using a C++ compiler. For example, you can use `g++`:

    ```bash
    g++ -o shell_sort shell_sort.cpp
    ```

4. Run the compiled executable:

    ```bash
    ./shell_sort
    ```

5. Follow the on-screen instructions to enter the size of the array and then the integers in any order.
6. The program will display the array before and after sorting using the shell sort algorithm.

## Algorithm

The program uses the following steps to sort the array using the shell sort algorithm:

1. Start with a gap value (typically half of the array size) and divide the array into smaller subarrays.
2. Perform insertion sort on each subarray.
3. Gradually reduce the gap until it becomes 1, performing insertion sort on the entire array.

## Example

```plaintext
Enter the size of the array:
5
Enter 5 integers in any order:
5 2 8 1 3
Before Sorting:
5 2 8 1 3
SHELL SORT

After Sorting:
1 2 3 5 8
