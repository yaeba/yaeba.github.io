---
title: "Valid N Queens"
tags: ["array"]
---

The `n` queens puzzle asks to place `n` queens on an n×n chessboard so that no two queens are attacking each other.

Given a two-dimensional integer `matrix` where `1` represents a queen and `0` represents an empty cell, return whether the board is valid solution to the puzzle.

**Constraints**

- `1 ≤ n ≤ 10` where `n` is the number of rows and columns in `matrix`

[https://binarysearch.com/problems/Valid-N-Queens](https://binarysearch.com/problems/Valid-N-Queens){:target="\_blank"}

## Examples

### Example 1

**Input**

- matrix =

```
[[1,0,0,0,0],
 [0,0,0,0,0],
 [0,0,0,0,1],
 [0,0,0,0,0],
 [0,0,0,1,0]]
```

**Output**

- answer = `False`

**Explanation**

There are no queens on the 2nd or 4th row.

### Example 2

**Input**

- matrix =

```
[[0,0,0,1,0],
 [0,1,0,0,0],
 [0,0,0,0,1],
 [0,0,1,0,0],
 [1,0,0,0,0]]
```

**Output**

- answer = `True`

**Explanation**

This is a valid n queens solution.

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Valid-N-Queens.py"></script>
