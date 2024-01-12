# Sorting Algorithms Repository

This repository contains implementations of various sorting algorithms in C. Below, you'll find information about the sorting algorithms included, an explanation of Big O notation, guidelines for selecting the best sorting algorithm, and details on stable sorting algorithms.

## Sorting Algorithms

1. **Bubble Sort (`0-bubble_sort.c`):**
   - Description: Bubble Sort is a simple sorting algorithm that repeatedly steps through the list, compares adjacent elements, and swaps them if they are in the wrong order.

2. **Merge Sort (`103-merge_sort.c`):**
   - Description: Merge Sort is a divide and conquer algorithm that divides the unsorted list into n sub-lists, each containing one element, and then repeatedly merges sub-lists to produce new sorted sub-lists until there is only one sub-list remaining.

3. **Quick Sort (`107-quick_sort_hoare.c`):**
   - Description: Quick Sort is a divide and conquer algorithm that selects a 'pivot' element from the array and partitions the other elements into two sub-arrays according to whether they are less than or greater than the pivot.

4. **Radix Sort (`105-radix_sort.c`):**
   - Description: Radix Sort is a non-comparative sorting algorithm that works by distributing elements into buckets according to their individual digits.

## Big O Notation

Big O notation is a mathematical notation that describes the limiting behavior of a function when the argument approaches infinity. In the context of algorithms, it expresses the upper bound of the worst-case time complexity. For example:
- **O(1):** Constant time complexity.
- **O(log n):** Logarithmic time complexity.
- **O(n):** Linear time complexity.
- **O(n^2):** Quadratic time complexity.

To evaluate the time complexity of an algorithm, analyze its performance as the input size grows.

## Selecting the Best Sorting Algorithm

Choosing the best sorting algorithm depends on various factors, including:
- **Input Size:** Different algorithms perform better on small or large datasets.
- **Stability:** If maintaining the order of equal elements is crucial, a stable sorting algorithm is preferred.
- **Memory Constraints:** Some algorithms require less memory than others.
- **Already Sorted Data:** Certain algorithms perform better when the data is partially or fully sorted.

## Stable Sorting Algorithm

A stable sorting algorithm preserves the relative order of equal elements in the sorted output. In other words, if two elements have equal keys in the original data, they will have the same relative order in the sorted result.

---

Feel free to explore the implementations in this repository and compare the performance of different sorting algorithms for your specific use case!
