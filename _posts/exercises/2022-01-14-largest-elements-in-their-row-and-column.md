---
title: "Largest Elements in Their Row and Column"
---

You are given a two-dimensional list of integers `matrix` containing `1`s and `0`s. Return the number of elements in `matrix` such that:

- `matrix[r][c] = 1`
- `matrix[r][j] = 0` for every `j ≠ c` and `matrix[i][c] = 0` for every `i ≠ r`

**Constraints**

- `0 ≤ n, m ≤ 250` where `n` and `m` are the number of rows and columns in `matrix`

[https://binarysearch.com/problems/Largest-Elements-in-Their-Row-and-Column](https://binarysearch.com/problems/Largest-Elements-in-Their-Row-and-Column){:target="\_blank"}

## Examples

### Example 1

**Input**

- matrix = `[[0, 0, 1], [1, 0, 0], [0, 1, 0]]`

**Output**

- answer = `3`

**Explanation**

We have `matrix[0][2]`, `matrix[1][0]` and `matrix[2][1]` meet the criteria.

### Example 2

**Input**

- matrix = `[[0, 0, 1], [1, 0, 0], [1, 0, 0]]`

**Output**

- answer = `1`

**Explanation**

Only `matrix[0][2]` meet the criteria. The other two `1`s share the same column.

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Largest-Elements-in-Their-Row-and-Column.py"></script>
