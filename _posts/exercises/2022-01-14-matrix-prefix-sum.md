---
title: "Matrix Prefix Sum"
tags: ["array"]
---

Given a two-dimensional integer `matrix`, return a new matrix `A` of the same dimensions where each element is set to `A[i][j] = sum(matrix[r][c]) for all r ≤ i, c ≤ j`.

**Constraints**

- `n, m ≤ 250` where `n` and `m` are the number of rows and columns in `matrix`
- `matrix[i][j] ≤ 2**12`

[https://binarysearch.com/problems/Matrix-Prefix-Sum](https://binarysearch.com/problems/Matrix-Prefix-Sum){:target="\_blank"}

## Examples

### Example 1

**Input**

- matrix = `[[2, 3], [5, 7]]`

**Output**

- answer = `[[2, 5], [7, 17]]`

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Matrix-Prefix-Sum.cpp"></script>
