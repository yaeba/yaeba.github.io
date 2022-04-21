---
title: "Minimum Dropping Path Sum"
tags: ["dynamic programming"]
---

You are given a two-dimensional list of integers `matrix`. Return the minimum sum you can get by taking a number in each row with the constraint that any row-adjacent numbers cannot be in the same column.

**Constraints**

- `1 ≤ n ≤ 250` where `n` is the number of rows in `matrix`
- `2 ≤ m ≤ 250` where `m` is the number of columns in `matrix`

[https://binarysearch.com/problems/Minimum-Dropping-Path-Sum](https://binarysearch.com/problems/Minimum-Dropping-Path-Sum){:target="\_blank"}

## Examples

### Example 1

**Input**

- matrix = `[[4, 5, -2], [2, 6, 1], [3, 1, 2]]`

**Output**

- answer = `1`

**Explanation**

We can take `-2` from the first row, `2` from the second row, and `1` from the last row.

### Example 2

**Input**

- matrix = `[[3, 0, 3], [2, 1, 3], [-2, 3, 0]]`

**Output**

- answer = `1`

**Explanation**

We can take `0` from the first row, `3` from the second row, and `-2` from the last row.

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Minimum-Dropping-Path-Sum.cpp"></script>
