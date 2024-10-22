# Sorting-Algorithms-CPP
Experiment 20


## Aim 
To use different sorting algorithms.

## Software Used 
VS Code

## Theory
#### Definition
Sorting algorithms are methods for arranging the elements of a list or array in a specific order, typically in ascending or descending order. In C++, there are several commonly used sorting algorithms, each with its own advantages and use cases. Some sorting algorithms include:

##### 1. Bubble Sort
A simple comparison-based algorithm that repeatedly steps through the list, compares adjacent elements, and swaps them if they are in the wrong order. It continues until no swaps are needed.
**Complexity:** O(n²)

##### 2. Selection Sort
This algorithm divides the input list into two parts: a sorted and an unsorted section. It repeatedly selects the smallest (or largest) element from the unsorted section and moves it to the end of the sorted section.
**Complexity:** O(n²)

##### 3. Insertion Sort
Insertion sort builds the sorted array one element at a time by repeatedly taking the next element and inserting it into the correct position within the sorted section.
**Complexity:** O(n²)  

---
#### Flow Chart

<p align="center">
    <img src="https://github.com/user-attachments/assets/817938fb-6d4e-4c6c-b632-a18e6a0fc46b" alt="SortingTYPE">
</p>

```
Sorting Algorithms
├── Comparison-Based Sorting
│   ├── Bubble Sort
│   │   ├── Simple implementation
│   │   └── Complexity: O(n²)
│   ├── Selection Sort
│   │   ├── Divides into sorted/unsorted
│   │   └── Complexity: O(n²)
│   ├── Insertion Sort
│   │   ├── Builds sorted array incrementally
│   │   └── Complexity: O(n²)
│   ├── Merge Sort
│   │   ├── Divide and conquer
│   │   └── Complexity: O(n log n)
│   ├── Quick Sort
│   │   ├── Uses pivot for partitioning
│   │   └── Complexity: O(n log n) average, O(n²) worst
│   └── Heap Sort
│       ├── Utilizes binary heap
│       └── Complexity: O(n log n)
├── Non-Comparison-Based Sorting
│   ├── Counting Sort
│   │   ├── Counts occurrences
│   │   └── Complexity: O(n + k)
│   └── Radix Sort
│       ├── Sorts digit by digit
│       └── Complexity: O(nk)
└── C++ Standard Library
    ├── `std::sort`
    └── Typically uses a hybrid sorting algorithm
```
## Algorithms

#### Insertion Sort

1. Initialize an array `arr` with the values: `{45, 23, 86, 12, 9}`.
2. Set `n` to the size of the array (5).
3. Loop through the array starting from the second element (index 1) to the last element:
   - a. Set `current` to the value of `arr[i]`.
   - b. Initialize `j` to `i - 1`.
   - c. While `j` is greater than or equal to 0 and `arr[j]` is greater than `current`:
     - i. Move `arr[j]` to `arr[j + 1]`.
     - ii. Decrement `j` by 1.
   - d. Place `current` in the correct position: `arr[j + 1] = current`.
4. After sorting, print the sorted array.

---


#### Selction Sort

1. Initialize an array `arr` with the values: `{23, 12, 56, 144, 78}`.
2. Set `n` to the size of the array (5).
3. Loop through the array from the first element to the second-to-last element:
   - a. Set `min_index` to the current index `i`.
   - b. Loop through the remaining unsorted elements:
     - i. If `arr[j]` is less than `arr[min_index]`, update `min_index` to `j`.
   - c. If `i` is not equal to `min_index`, swap the elements at index `i` and `min_index`.
4. After sorting, print the sorted array.

---


#### Bubble Sort

1. Initialize an array `arr` with the values: `{23, 12, 56, 144, 78}`.
2. Set `n` to the size of the array (5).
3. Loop through the array from the first element to the second-to-last element:
   - a. For each iteration, loop through the array up to the last unsorted element:
     - i. If `arr[j]` is greater than `arr[j + 1]`, swap the two elements.
4. After sorting, print the sorted array.




## Conclusion
We learnt to use different sorting algorithms to efficiently sort items in a data structure.
