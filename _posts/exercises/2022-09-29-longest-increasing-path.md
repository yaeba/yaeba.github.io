---
title: "Longest Increasing Path"
tags: ["dynamic programming"]
---

Given a two-dimensional integer `matrix`, find the length of the longest strictly increasing path. You can move up, down, left, or right.

**Constraints**

- `n, m ≤ 500` where `n` and `m` are the number of rows and columns in `matrix`

[https://binarysearch.com/problems/Longest-Increasing-Path](https://binarysearch.com/problems/Longest-Increasing-Path){:target="\_blank"}

## Examples

### Example 1

**Input**

- matrix =

```
[[1,3,5],
 [0,4,6],
 [2,2,9]]
```

**Output**

- answer = `6`

**Explanation**

The longest path is `[0, 1, 3, 5, 6, 9]`

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Longest-Increasing-Path.py"></script>
