---
title: "Range Query on Two Dimensional List"
tags: ["data structure", "prefix sum", "array"]
---

Implement a data structure with the following methods:

- `RangeSum(int[][] matrix)` constructs a new instance with the given `matrix`.
- `total(int row0, int col0, int row1, int col1)` returns the sum of all cells `matrix[r][c]` where `row0 ≤ r ≤ row1` and `col0 ≤ c ≤ col1`.

**Constraints**

- `n, m ≤ 250` where `n` and `m` are the number of rows and columns in `matrix`
- `k ≤ 100,000` where `k` is the number of calls to `total`

[https://binarysearch.com/problems/Range-Query-on-Two-Dimensional-List](https://binarysearch.com/problems/Range-Query-on-Two-Dimensional-List){:target="\_blank"}

## Examples

### Example 1

**Input**

- methods = `['constructor', 'total', 'total']`
- arguments = `[[[[1, 2, 3], [4, 5, 6]]], [0, 0, 1, 1], [0, 1, 0, 2]]`

**Output**

- answer = `[None, 12, 5]`

**Explanation**

```
r = RangeSum([[[1,2,3],[4,5,6]])
r.total(0, 0, 1, 1) == 12 # sum([1, 2], [4, 5]])
r.total(0, 1, 0, 2) == 5 # sum([[2, 3]])
```

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Range-Query-on-Two-Dimensional-List.cpp"></script>
