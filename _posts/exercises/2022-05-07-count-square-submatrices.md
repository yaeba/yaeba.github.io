---
title: "Count Square Submatrices"
tags: ["dynamic programming"]
---

Given a two-dimensional list of integers `matrix` containing `1`s and `0`s, return the total number of square submatrices with all `1` s.

**Constraints**

- `n, m ≤ 250` where `n` and `m` are the number of rows and columns in `matrix`.

[https://binarysearch.com/problems/Count-Square-Submatrices](https://binarysearch.com/problems/Count-Square-Submatrices){:target="\_blank"}

## Examples

### Example 1

**Input**

- matrix =

```
[[1,1,0],
 [1,1,0]]
```

**Output**

- answer = `5`

**Explanation**

There's `4` of `1 × 1` squares and `1` `2 × 2` square.

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Count-Square-Submatrices.py"></script>
