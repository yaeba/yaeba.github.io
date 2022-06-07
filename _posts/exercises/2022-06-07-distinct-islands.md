---
title: "Distinct Islands"
---

Given a two-dimensional integer `matrix` of `1`s and `0`s, return the number of distinct "islands" in the matrix. A `1` represents land and `0` represents water, so an island is a group of 1s that are neighboring whose perimeter is surrounded by water. Two islands are distinct if their shapes are different.

**Constraints**

- `n, m ≤ 100` where `n` and `m` are the number of rows and columns in `matrix`

[https://binarysearch.com/problems/Distinct-Islands](https://binarysearch.com/problems/Distinct-Islands){:target="\_blank"}

## Examples

### Example 1

**Input**

- matrix = `[[1, 0, 0, 0, 0], [0, 0, 1, 1, 0], [0, 1, 1, 0, 0], [0, 0, 0, 0, 0], [1, 1, 0, 1, 1], [1, 1, 0, 1, 1]]`

**Output**

- answer = `3`

**Explanation**

This matrix has 4 islands, but only 3 distinct islands since the islands at the bottom are identical.

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Distinct-Islands.cpp"></script>
