---
title: "Minimum Dropping Path Sum With Column Distance Constraint"
tags: ["array", "dynamic programming"]
---

You are given a two-dimensional list of integers `matrix`. Return the minimum sum you can get by taking a number in each row with the constraint that any row-adjacent numbers can only differ in columns by at most one unit.

**Constraints**

- `1 ≤ n ≤ 250` where `n` is the number of rows in `matrix`
- `2 ≤ m ≤ 250` where `m` is the number of columns in `matrix`

[https://binarysearch.com/problems/Minimum-Dropping-Path-Sum-With-Column-Distance-Constraint](https://binarysearch.com/problems/Minimum-Dropping-Path-Sum-With-Column-Distance-Constraint){:target="\_blank"}

## Examples

### Example 1

**Input**

- matrix = `[[3, 0, 3], [1, 4, 3], [-2, 3, -3]]`

**Output**

- answer = `-1`

**Explanation**

We can take `0` from the first row, `1` from the second row, and `-2` from the last row.

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Minimum-Dropping-Path-Sum-With-Column-Distance-Constraint.cpp"></script>
