
# Sorting Algorithms in C

This project implements a variety of sorting algorithms in C. It includes both well-known sorting techniques and some more advanced methods. The purpose of this project is to understand and compare the performance and behavior of different sorting algorithms.

## Sorting Algorithms Implemented

The following sorting algorithms are included:

1. **Bubble Sort**: A simple comparison-based algorithm where each element is compared with the next and swapped if necessary.
2. **Insertion Sort**: Builds the sorted array one item at a time by repeatedly picking the next element and inserting it into its correct position.
3. **Heap Sort**: A comparison-based sorting algorithm that uses a binary heap data structure.
4. **Quick Sort**: A divide-and-conquer algorithm that picks a pivot element and partitions the array around it, recursively sorting the sub-arrays.
5. **Selection Sort**: Selects the smallest element from an unsorted portion and places it at the beginning.
6. **Shaker Sort**: A variation of bubble sort that works in both directions, improving efficiency.
7. **Merge Sort**: A divide-and-conquer algorithm that splits the array into halves, sorts them, and merges the sorted halves.

## Compilation Instructions

To compile the project, simply run:

```bash
gcc main.c sort.c
```

## Code Usage

The program uses a small test array in the `main` function. You can modify this array or add new tests to experiment with different data sets. Here's a brief example of how the sorting functions work:

```c
int a[] = {110, 0, 1, 21, 12, 33333, -1, -1};
int len = sizeof(a) / sizeof(a[0]);

bubble_sort(a, len);
```

This will sort the array `a` in ascending order using the **Bubble Sort** algorithm.

## Example Output

Here's an example of the output when running the program:

```
Bubble Sort:
Before: 110 0 1 21 12 33333 -1 -1
After: -1 -1 0 1 12 21 110 33333

Insertion Sort:
Before: 110 0 1 21 12 33333 -1 -1
After: -1 -1 0 1 12 21 110 33333

Heap Sort:
Before: 110 0 1 21 12 33333 -1 -1
After: -1 -1 0 1 12 21 110 33333

Quick Sort:
Before: 110 0 1 21 12 33333 -1 -1
After: -1 -1 0 1 12 21 110 33333

Selection Sort:
Before: 110 0 1 21 12 33333 -1 -1
After: -1 -1 0 1 12 21 110 33333

Shaker Sort:
Before: 110 0 1 21 12 33333 -1 -1
After: -1 -1 0 1 12 21 110 33333

Merge Sort:
Before: 110 0 1 21 12 33333 -1 -1
After: -1 -1 0 1 12 21 110 33333
```
