---
title: "Bipartite Graph"
tags: ["queue", "graph"]
---

Given an undirected graph represented as an adjacency list, return whether the graph is bipartite.

**Constraints**

- `n, m ≤ 250` where `n` and `m` are the number of rows and columns in `graph`

[https://binarysearch.com/problems/Bipartite-Graph](https://binarysearch.com/problems/Bipartite-Graph){:target="\_blank"}

## Examples

### Example 1

**Input**

- graph =

```
[[1],
 [0]]
```

**Output**

- answer = `True`

**Explanation**

This is bipartite since the node `1` can belong in set `A` and node `2` can belong in set `B`. Then the edges `0 -> 1` and `1 -> 0` has one node in `A` and one node in `B`

### Example 2

**Input**

- graph =

```
[[list([1, 2, 3]),list([0, 2]),list([0, 1, 3]),list([0, 2])]]
```

**Output**

- answer = `False`

**Explanation**

No matter how the nodes are partitioned, an edge will belong to the same set.

### Example 3

**Input**

- graph =

```
[[2,3],
 [2,3],
 [0,1],
 [0,1]]
```

**Output**

- answer = `True`

**Explanation**

`0` and `1` can belong in set `A` and `2` and `3` can belong in set `B`.

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Bipartite-Graph.py"></script>
