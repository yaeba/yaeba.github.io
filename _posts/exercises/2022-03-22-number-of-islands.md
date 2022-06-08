---
title: "Number of Islands"
tags: ["graph"]
---

Given a two-dimensional integer `matrix` of 1s and 0s, return the number of "islands" in the matrix. A `1` represents land and `0` represents water, so an island is a group of 1s that are neighboring whose perimeter is surrounded by water.

Note: Neighbors can only be directly horizontal or vertical, not diagonal.

**Constraints**

- `n, m ≤ 100` where `n` and `m` are the number of rows and columns in `matrix`.

[https://binarysearch.com/problems/Number-of-Islands](https://binarysearch.com/problems/Number-of-Islands){:target="\_blank"}

## Examples

### Example 1

**Input**

- matrix =

```
[[1,1],
 [1,0]]
```

**Output**

- answer = `1`

### Example 2

**Input**

- matrix =

```
[[0,1],
 [1,0]]
```

**Output**

- answer = `2`

### Example 3

**Input**

- matrix =

```
[[1,0,0,0,0],
 [0,0,1,1,0],
 [0,1,1,0,0],
 [0,0,0,0,0],
 [1,1,0,0,1],
 [1,1,0,0,1]]
```

**Output**

- answer = `4`

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Number-of-Islands.cpp"></script>
