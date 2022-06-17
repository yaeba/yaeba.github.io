---
title: "Paint Bucket"
tags: ["graph"]
---

You are given a two dimensional array `matrix`, containing strings "r", "g", and "b". Perform a floodfill operation at row `r`, column `c` with the color `target`.

A floodfill operation replaces elements that are connected to `matrix[r][c]` (up/right/down/left) and have the same color as `matrix[r][c]` with the color of `target`.

**Constraints**

- `n, m ≤ 200` where `n` and `m` are the number of rows and columns in `matrix`

[https://binarysearch.com/problems/Paint-Bucket](https://binarysearch.com/problems/Paint-Bucket){:target="\_blank"}

## Examples

### Example 1

**Input**

- matrix =

```
[['r','r','r'],
 ['r','g','b'],
 ['g','b','b']]
```

- r = `0`
- c = `0`
- target = `g`

**Output**

- answer = `[['g', 'g', 'g'], ['g', 'g', 'b'], ['g', 'b', 'b']]`

**Explanation**

The red elements connected to matrix[0][0] are replaced with "g".

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Paint-Bucket.py"></script>
