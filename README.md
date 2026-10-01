# HackerRank 3rd Sem Portfolio

**HackerRank Profile:** [https://www.hackerrank.com/profile/h25020102436]

## Overview
This repository contains optimal Python implementations for the 5 mandatory HackerRank studio submission problems. All solutions pass 100% of the test cases while maintaining target time and space complexity.

---

## Summary of Solutions & Complexity Analysis

| No. | Problem Name | Topic / Category | Time Complexity | Space Complexity | Approach Description |
|---|---|---|---|---|---|
| 1 | Diagonal Difference | 2D Arrays / Matrices | O(N) | O(1) | Single-pass traversal calculating primary `arr[i][i]` and secondary `arr[i][n-1-i]` diagonal sums simultaneously. |
| 2 | Dynamic Array | Data Structures / Vectors | O(N + Q) | O(N) | Dynamic 2D sequence list with index computation using bitwise XOR (`x ^ lastAnswer`). |
| 3 | Time Conversion | Strings & Logic | O(1) | O(1) | Period extraction (AM/PM) and 12-to-24 hour modular arithmetic formatting. |
| 4 | Compare the Triplets | Basic Implementation | O(1) | O(1) | Element-wise conditional comparisons across fixed 3-element lists. |
| 5 | Sparse Arrays | Hash Maps / Strings | O(N + Q) | O(N) | Frequency mapping using `collections.Counter` to allow O(1) string lookup per query. |

---

## Technical Approach & Algorithmic Optimization
- **Optimization Strategy:** Hash maps were utilized to bring string query times from quadratic to linear time, while single-pass loop indexing minimized matrix processing steps.
- **Languages Used:** Python 3
- **Test Case Status:** All 5 problems successfully passed 100% of test cases on HackerRank.
