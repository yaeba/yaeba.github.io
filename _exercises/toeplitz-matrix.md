---
title: "Toeplitz Matrix"
tags: ["array"]
---

Given a two-dimensional matrix of integers `matrix`, determine whether it's a Toeplitz matrix. A Toeplitz is one where every diagonal descending from left to right has the same value.

**Constraints**

- `n, m ≤ 250` where `n` and `m` are the number of rows and columns in `matrix`

[https://binarysearch.com/problems/Toeplitz-Matrix](https://binarysearch.com/problems/Toeplitz-Matrix){:target="\_blank"}

## Examples

### Example 1

**Input**

- matrix = `[[0, 1, 2], [3, 0, 1], [4, 3, 0], [5, 4, 3]]`

**Output**

- answer = `True`

### Example 2

**Input**

- matrix = `[[1, 0, 0], [0, 0, 0], [0, 0, 1]]`

**Output**

- answer = `False`

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Toeplitz-Matrix.cpp"></script>
