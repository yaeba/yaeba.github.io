---
title: "Interval Union"
tags: ["stack", "greedy"]
---

Given a two-dimensional integer list `intervals` representing unsorted inclusive intervals, return their union in sorted order.

**Constraints**

- `n ≤ 100,000` where `n` is the length of `intervals`

[https://binarysearch.com/problems/Interval-Union](https://binarysearch.com/problems/Interval-Union){:target="\_blank"}

## Examples

### Example 1

**Input**

- intervals = `[[0, 5], [4, 6]]`

**Output**

- answer = `[[0, 6]]`

### Example 2

**Input**

- intervals = `[[5, 6], [1, 2]]`

**Output**

- answer = `[[1, 2], [5, 6]]`

### Example 3

**Input**

- intervals = `[[1, 2], [3, 4]]`

**Output**

- answer = `[[1, 2], [3, 4]]`

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Interval-Union.py"></script>
