---
title: "Collecting Coins"
tags: ["dynamic programming"]
---

You are given a two-dimensional integer `matrix` where each cell represents number of coins in that cell. Assuming we start at `matrix[0][0]`, and can only move right or down, find the maximum number of coins you can collect by the bottom right corner.

**Constraints**

- `n, m ≤ 100` where `n` and `m` are the number of rows and columns in `matrix`.

[https://binarysearch.com/problems/Collecting-Coins](https://binarysearch.com/problems/Collecting-Coins){:target="\_blank"}

## Examples

### Example 1

**Input**

- matrix = `[[0, 3, 1, 1], [2, 0, 0, 4], [1, 5, 3, 1]]`

**Output**

- answer = `12`

**Explanation**

We take the following path: [0, 2, 1, 5, 3, 1]

### Example 2

**Input**

- matrix = `[[0, 3, 1, 1], [2, 0, 0, 4]]`

**Output**

- answer = `9`

**Explanation**

We take the following path: [0, 3, 1, 1, 4]

### Example 3

**Input**

- matrix = `[[0, 2, 1], [2, 5, 0], [4, 1, 3]]`

**Output**

- answer = `11`

**Explanation**

We take the following path: [0, 2, 5, 1, 3]

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Collecting-Coins.cpp"></script>
