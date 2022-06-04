---
title: "Enclosed Islands"
---

You are given a two-dimensional integer `matrix` of `1`s and `0`s. A `1` represents land and `0` represents water. From any land cell you can move up, down, left or right to another land cell or go off the matrix.

Return the number of land cells from which we cannot go off the matrix.

**Constraints**

- `n, m ≤ 250` where `n` and `m` are the number of rows and columns in `matrix`

[https://binarysearch.com/problems/Enclosed-Islands](https://binarysearch.com/problems/Enclosed-Islands){:target="\_blank"}

## Examples

### Example 1

**Input**

- matrix = `[[0, 0, 0, 1], [0, 1, 1, 0], [0, 1, 1, 0], [0, 0, 0, 0]]`

**Output**

- answer = `4`

**Explanation**

There's `4` land squares in the middle from which we cannot walk off the matrix.

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Enclosed-Islands.cpp"></script>
