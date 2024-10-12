# Insertion Sort Homework

## Problem
Sort the array using the Insertion Sort algorithm:

**Initial array:**  
`[22, 27, 16, 2, 18, 6]`

## Steps:

1. The first two elements are already sorted, so no change is needed:  
   `[22, 27, 16, 2, 18, 6]`

2. Insert the third element:  
   `[22, 27, 16, 2, 18, 6] -> [16, 22, 27, 2, 18, 6]`

3. Insert the fourth element:  
   `[16, 22, 27, 2, 18, 6] -> [2, 16, 22, 27, 18, 6]`

4. Insert the fifth element:  
   `[2, 16, 22, 27, 18, 6] -> [2, 16, 18, 22, 27, 6]`

5. Insert the sixth element:  
   `[2, 16, 18, 22, 27, 6] -> [2, 6, 16, 18, 22, 27]`

**Sorted array:**  
`[2, 6, 16, 18, 22, 27]`

---

## Time Complexity

- **Worst case:** `O(n^2)`
- **Best case:** `O(n)` (if the array is already sorted)
- **Average case:** `O(n^2)`

### Notes:
- `n` represents the number of elements in the array.
- Insertion Sort is efficient for small arrays but has performance limitations with larger datasets.

---

**Author:** [Ahmet Yunus Turna]
