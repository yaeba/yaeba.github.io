---
title: "Count Rectangular Submatrices"
---

Given a two-dimensional list of integers `matrix` containing `1`s and `0`s, return the total number of submatrices with all `1` s.

**Constraints**

- `n, m ≤ 250` where `n` and `m` are the number of rows and columns in `matrix`.

[https://binarysearch.com/problems/Count-Rectangular-Submatrices](https://binarysearch.com/problems/Count-Rectangular-Submatrices){:target="\_blank"}

## Examples

### Example 1

**Input**

- matrix =

```
[[1,1,0],
 [1,1,0],
 [0,0,0]]
```

**Output**

- answer = `9`

**Explanation**

There's four `1 x 1` matrices. Theres two `2 x 1` matrices. There's two `1 x 2` matrices. And there's one `2 x 2` matrix.

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Count-Rectangular-Submatrices.py"></script>
