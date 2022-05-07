---
title: "Largest Square Submatrix"
tags: ["dynamic programming"]
---

Given a two-dimensional integer `matrix`, return the area of the largest square of `1` s.

**Constraints**

- `n, m ≤ 200` where `n` and `m` are the number of rows and columns in `matrix`

[https://binarysearch.com/problems/Largest-Square-Submatrix](https://binarysearch.com/problems/Largest-Square-Submatrix){:target="\_blank"}

## Examples

### Example 1

**Input**

- matrix = `[[0, 0, 0, 0, 0, 1, 1], [0, 0, 0, 0, 0, 1, 1], [1, 1, 1, 1, 0, 0, 0], [1, 1, 1, 1, 0, 0, 0], [1, 1, 1, 1, 0, 0, 0], [1, 1, 1, 1, 0, 0, 0]]`

**Output**

- answer = `16`

**Explanation**

The bottom left square has a bigger area than the top right square.

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Largest-Square-Submatrix.py"></script>
