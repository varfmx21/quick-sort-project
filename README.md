# Quick Sort Algorithm in C++

## Description
In this activity, students will implement the **Quick Sort** algorithm in C++, a highly efficient sorting method based on the divide-and-conquer approach. Quick Sort selects a pivot, organizes elements around this pivot (with smaller elements on the left and larger elements on the right), and then recursively applies the same process to the subarrays generated.

## Algorithm Overview

### Quick Sort
- **Quick Sort** is based on these steps:
  1. **Partitioning**: Choose a pivot element and rearrange the array so that all elements less than the pivot are on the left and all greater are on the right.
  2. **Recursion**: Recursively apply the same process to the left and right subarrays.
  3. **Base Case**: The process continues until subarrays contain a single element or are empty, at which point the array is fully sorted.

- It uses a partition function to determine the pivot's final position and to partition the list.

## Code Explanation
- The function `partition` rearranges the elements around the pivot.
- `quickSort` is recursively applied to the left and right parts of the array.
- The main function initializes the array and calls `quickSort` to sort it, printing the result.

### Time and Space Complexity
- **Time Complexity**: 
  - Best and average case: O(n log n)
  - Worst case: O(n²), if the pivot always ends up being the smallest or largest element.
  
- **Space Complexity**: O(log n) due to recursive calls on the stack.

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/quick-sort-algorithm
