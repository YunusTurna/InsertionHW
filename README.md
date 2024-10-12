# Insertion Sort Homework

## Problem 1
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
- **This case:** `Average Case = O(n^2)`

---

## Problem 2
Sort the array using the Selection Sort algorithm:  
**Initial array:**  
`[7, 3, 5, 8, 2, 9, 4, 15, 6]`

**Steps:**

1. Select the first element (minimum is `2`):  
   `[2, 3, 5, 8, 7, 9, 4, 15, 6]`

2. Select the second element (minimum is `3`):  
   `[2, 3, 5, 8, 7, 9, 4, 15, 6]` (no change)

3. Select the third element (minimum is `4`):  
   `[2, 3, 4, 8, 7, 9, 5, 15, 6]`

4. Select the fourth element (minimum is `5`):  
   `[2, 3, 4, 5, 7, 9, 8, 15, 6]`

5. Continue sorting:  
   Select the next minimum (`6`):  
   `[2, 3, 4, 5, 6, 9, 8, 15, 7]`

### Notes:
- `n` represents the number of elements in the array.
- Insertion Sort is efficient for small arrays but has performance limitations with larger datasets.
- Selection Sort has a consistent performance of `O(n^2)` for all cases.

---

**Author:** Ahmet Yunus Turna
