---
title: "Surrounded Islands"
---

You are given a two-dimensional integer matrix `matrix` containing `1`s and `0`s. `1` represents land and `0` represents water. An island is a group of 1s that are neighboring whose perimeter is surrounded by water. Return the number of completely surrounded islands.

**Constraints**

- `n, m ≤ 250` where `n` and `m` are the number of rows and columns in `matrix`.

[https://binarysearch.com/problems/Surrounded-Islands](https://binarysearch.com/problems/Surrounded-Islands){:target="\_blank"}

## Examples

### Example 1

**Input**

- matrix =

```
[[1,1,0,0,0],
 [0,0,0,0,0],
 [0,1,1,1,0],
 [0,1,0,1,0],
 [0,1,1,1,0],
 [0,0,0,0,0]]
```

**Output**

- answer = `1`

**Explanation**

There's `2` islands but only the middle island is completely surrounded.

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Surrounded-Islands.cpp"></script>
