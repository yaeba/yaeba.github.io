---
title: "Zero Matrix"
tags: ["hash table"]
---

Given a two-dimensional matrix of integers, for each zero in the original matrix, replace all values in its row and column with zero, and return the resulting matrix.

**Constraints**

- `n * m ≤ 100,000` where `n` and `m` are the number of rows and columns in `matrix`

[https://binarysearch.com/problems/Zero-Matrix](https://binarysearch.com/problems/Zero-Matrix){:target="\_blank"}

## Examples

### Example 1

**Input**

- matrix = `[[5, 0, 0, 5, 8], [9, 8, 10, 3, 9], [0, 7, 2, 3, 1], [8, 0, 6, 7, 2], [4, 1, 8, 5, 10]]`

**Output**

- answer = `[[0, 0, 0, 0, 0], [0, 0, 0, 3, 9], [0, 0, 0, 0, 0], [0, 0, 0, 0, 0], [0, 0, 0, 5, 10]]`

**Explanation**

These rows contain a `0`: `[0, 2, 3]` and the returned matrix contains `0` in those rows.
These columns contain a `0`: `[0, 1, 2]` and the returned matrix contains `0` in those columns.

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Zero-Matrix.cpp"></script>
