---
title: "Count Submatrices That Sum Target"
---

You are given a two-dimensional integer `matrix` and an integer `target`. Return the number of submatrices in `matrix` whose sum equals `target`.

**Constraints**

- `0 ≤ n, m ≤ 100` where `n` and `m` are the number of rows and columns in `matrix`

[https://binarysearch.com/problems/Count-Submatrices-That-Sum-Target](https://binarysearch.com/problems/Count-Submatrices-That-Sum-Target){:target="\_blank"}

## Examples

### Example 1

**Input**

- matrix =

```
[[ 0,-1],
 [ 0, 0]]
```

- target = `0`

**Output**

- answer = `5`

**Explanation**

We have three `1 x 1` submatrices, one `2 x 1` submatrix and one `1 x 2` submatrix.

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Count-Submatrices-That-Sum-Target.py"></script>
