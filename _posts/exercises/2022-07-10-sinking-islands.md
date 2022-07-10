---
title: "Sinking Islands"
tags: ["graph"]
---

Given an 2D `matrix` of `0`s and `1`s, a `1` represents land and `0` represents water. An island is a group of `1`'s that are surrounded by `0`s or by the border. Find all the islands that are completely surrounded by water and modify them into `0`s.

An island is completed surrounded by water if all of the neighbours are water (that is, none of the neighbours are borders).

Note: Neighbours can only be directly horizontal or vertical, not diagonal.

**Constraints**

- `n, m ≤ 250` where `n` and `m` are the number of rows and columns in `matrix`

[https://binarysearch.com/problems/Sinking-Islands](https://binarysearch.com/problems/Sinking-Islands){:target="\_blank"}

## Examples

### Example 1

**Input**

- board =

```
[[1,1],
 [1,0]]
```

**Output**

- answer = `[[1, 1], [1, 0]]`

**Explanation**

The island is not submerged since it touches some of the borders.

### Example 2

**Input**

- board =

```
[[1,0,0,0],
 [0,1,1,0],
 [0,0,0,0]]
```

**Output**

- answer = `[[1, 0, 0, 0], [0, 0, 0, 0], [0, 0, 0, 0]]`

**Explanation**

The island in the middle `[(1, 1), (1, 2)]` is completely submerged.

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Sinking-Islands.cpp"></script>
