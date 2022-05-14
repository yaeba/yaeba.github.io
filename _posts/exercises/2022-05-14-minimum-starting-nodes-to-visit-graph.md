---
title: "Minimum Starting Nodes to Visit Graph"
tags: ["graph"]
---

You are given a two-dimensional list of integers `edges` representing a connected, directed, acyclic graph. Each element in `edges` contains `[u, v]` meaning there is an edge from `u` to `v`. Return the minimum list of nodes from which we can visit every node in the graph, sorted in ascending order.

**Constraints**

- `0 ≤ n ≤ 100,000` where `n` is the length of `edges`

[https://binarysearch.com/problems/Minimum-Starting-Nodes-to-Visit-Graph](https://binarysearch.com/problems/Minimum-Starting-Nodes-to-Visit-Graph){:target="\_blank"}

## Examples

### Example 1

**Input**

- edges = `[[1, 0], [2, 0], [3, 2], [4, 3]]`

**Output**

- answer = `[1, 4]`

### Example 2

**Input**

- edges = `[[0, 1], [1, 2], [3, 2]]`

**Output**

- answer = `[0, 3]`

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Minimum-Starting-Nodes-to-Visit-Graph.py"></script>
