---
title: "Cycle Detection in a Matrix"
---

You are given a two-dimensional list of integers `matrix`. Return whether you can start from some cell, move adjacent to neighboring cells (up, down, left, right) of the same value, and come back to the same starting cell. You can’t revisit a cell you last visited.

**Constraints**

- `n, m ≤ 250` where `n` and `m` are the number of rows and columns in `matrix`

[https://binarysearch.com/problems/Cycle-Detection-in-a-Matrix](https://binarysearch.com/problems/Cycle-Detection-in-a-Matrix){:target="\_blank"}

## Examples

### Example 1

**Input**

- matrix =

```
[[2,1,1,1],
 [2,1,0,1],
 [2,1,1,1]]
```

**Output**

- answer = `True`

**Explanation**

We can follow the `1`s to form a cycle.

### Example 2

**Input**

- matrix =

```
[[2,1,1,1],
 [2,1,0,3],
 [2,1,1,1]]
```

**Output**

- answer = `False`

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Cycle-Detection-in-a-Matrix.py"></script>
