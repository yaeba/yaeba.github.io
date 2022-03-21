---
title: "Largest Island Area"
tags: ["graph"]
---

You are given a two-dimensional integer `matrix` of `1`s and `0`s. A `1` represents land and `0` represents water, so an island is a group of 1s that are neighboring whose perimeter is surrounded by water. You can assume that the edges of the matrix are surrounded by water.

Return the area of the largest island in `matrix`.

**Constraints**

- `n, m ≤ 250` where `n` and `m` are the number of rows and columns in `matrix`

[https://binarysearch.com/problems/Largest-Island-Area](https://binarysearch.com/problems/Largest-Island-Area){:target="\_blank"}

## Examples

### Example 1

**Input**

- matrix = `[[0, 0, 0, 1, 1, 1, 1], [0, 0, 0, 0, 0, 0, 0], [0, 1, 1, 1, 1, 1, 0], [0, 0, 1, 1, 0, 0, 0], [0, 0, 0, 0, 0, 1, 1], [0, 0, 0, 0, 0, 0, 0]]`

**Output**

- answer = `7`

**Explanation**

The largest island in the center has an area of 7 units.

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Largest-Island-Area.cpp"></script>
