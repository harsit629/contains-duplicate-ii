# contains-duplicate-ii
LeetCode Problem: Contains Duplicate II (Java)
## Problem
Check if an array contains duplicate elements within distance k.

## Approach
- Use HashMap to store the last index of each number
- If the same number appears again and index difference ≤ k, return true

## Complexity
- Time: O(n)
- Space: O(n)
