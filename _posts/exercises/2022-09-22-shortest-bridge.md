---
title: "Shortest Bridge"
tags: ["graph"]
---

Given a two-dimensional list of integers `matrix` containing `0`s and `1`s, `0` represents water and `1` represents land.

An island is a group of connecting `1`s in 4 directions that are either surrounded by `0`s or by the edges.
Find the shortest bridge that connects two islands.

It is guaranteed that there are two and only two islands.

**Constraints**

- `n, m ≤ 250` where `n` and `m` are the number of rows and columns in `matrix`

[https://binarysearch.com/problems/Shortest-Bridge](https://binarysearch.com/problems/Shortest-Bridge){:target="\_blank"}

## Examples

### Example 1

**Input**

- matrix =

```
[[0,1],
 [1,0]]
```

**Output**

- answer = `1`

**Explanation**

Either of the two water elements can be used as the bridge.

### Example 2

**Input**

- matrix =

```
[[1,0,0],
 [0,0,0],
 [0,0,1]]
```

**Output**

- answer = `3`

**Explanation**

There's six shortest bridges such as `[(0, 1), (0, 2), (1, 2)]` or `[(1, 0), (2, 0), (2, 1)]`

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Shortest-Bridge.py"></script>
