---
title: "Connect Cartesian Coordinates"
tags: ["union find"]
---

You are given a two-dimensional list of integers `points` where each element contains `[x, y]` representing a cartesian coordinate. We can make an undirected edge between two points `(x0, y0)` and `(x1, y1)`, which costs `abs(x0 - x1) + abs(y0 - y1)`.

Given that we can connect any number of points, return the minimum cost necessary such that every point is connected by a path.

**Constraints**

- `0 ≤ n ≤ 1,000` where `n` is the length of `points`

[https://binarysearch.com/problems/Connect-Cartesian-Coordinates](https://binarysearch.com/problems/Connect-Cartesian-Coordinates){:target="\_blank"}

## Examples

### Example 1

**Input**

- points =

```
[[ 0, 0],
 [ 0, 1],
 [ 0,-1],
 [ 1, 0],
 [-1, 0]]
```

**Output**

- answer = `4`

**Explanation**

We can create an edge from `(0, 0)` to every other point.

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Connect-Cartesian-Coordinates.py"></script>
