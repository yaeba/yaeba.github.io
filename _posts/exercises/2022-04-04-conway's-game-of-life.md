---
title: "Conway's Game of Life"
---

You are given a two dimensional `matrix` where a `1` represents a live cell and a `0` represents a dead cell. A cell's (living or dead) neighbors are its immediate horizontal, vertical and diagonal cells. Compute the next state of the matrix using these rules:

- Any living cell with two or three living neighbors lives.
- Any dead cell with three living neighbors becomes a live cell.
- All other cells die.

**Constraints**

- `n, m ≤ 500` where `n` and `m` are the number of rows and columns in `matrix`

[https://binarysearch.com/problems/Conway's-Game-of-Life](https://binarysearch.com/problems/Conway's-Game-of-Life){:target="\_blank"}

## Examples

### Example 1

**Input**

- matrix = `[[1, 1, 1, 0], [0, 1, 0, 1], [0, 1, 0, 0], [1, 1, 0, 1]]`

**Output**

- answer = `[[1, 1, 1, 0], [0, 0, 0, 0], [0, 1, 0, 0], [1, 1, 1, 0]]`

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Conway's-Game-of-Life.py"></script>
