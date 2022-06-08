---
title: "Matrix Search"
tags: ["array"]
---

Given a two-dimensional integer `matrix`, where every row and column is sorted in ascending order, find the `k`th (0-indexed) smallest number.

**Constraints**

- `n, m ≤ 250` where `n` and `m` are the number of rows and columns in `matrix`

[https://binarysearch.com/problems/Matrix-Search](https://binarysearch.com/problems/Matrix-Search){:target="\_blank"}

## Examples

### Example 1

**Input**

- matrix =

```
[[ 1, 3,30],
 [ 2, 3,31],
 [ 5, 5,32]]
```

- k = `4`

**Output**

- answer = `5`

### Example 2

**Input**

- matrix =

```
[[1,2,3]]
```

- k = `0`

**Output**

- answer = `1`

### Example 3

**Input**

- matrix =

```
[[1],
 [2],
 [3]]
```

- k = `2`

**Output**

- answer = `3`

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Matrix-Search.cpp"></script>
<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Matrix-Search.py"></script>
