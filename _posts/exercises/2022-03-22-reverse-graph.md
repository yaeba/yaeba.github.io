---
title: "Reverse Graph"
tags: ["graph"]
---

Given a directed graph represented as an adjacency list, return its reverse so if an edge goes from A to B, it now goes from B to A.

Each list in the adjacency list should be sorted in ascending order.

**Constraints**

- `0 ≤ n, m ≤ 250` where `n` is the number of rows and `m` is the maximum number of columns in `graph`

[https://binarysearch.com/problems/Reverse-Graph](https://binarysearch.com/problems/Reverse-Graph){:target="\_blank"}

## Examples

### Example 1

**Input**

- graph = `[[1], [2], []]`

**Output**

- answer = `[[], [0], [1]]`

**Explanation**

In this example the nodes start off 0 -> 1 -> 2 and then become 0 <- 1 <- 2.

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Reverse-Graph.py"></script>
