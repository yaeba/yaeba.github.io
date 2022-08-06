---
title: "Detecting an Odd Length Cycle"
tags: ["graph"]
---

Given an undirected graph as an adjacency list, return whether the graph has an odd length cycle.

**Constraints**

- `n, m ≤ 250` where `n` and `m` are the number of rows and columns in `graph`

[https://binarysearch.com/problems/Detecting-an-Odd-Length-Cycle](https://binarysearch.com/problems/Detecting-an-Odd-Length-Cycle){:target="\_blank"}

## Examples

### Example 1

**Input**

- graph =

```
[[1],
 [0]]
```

**Output**

- answer = `False`

**Explanation**

There is an even length cycle, not odd.

### Example 2

**Input**

- graph =

```
[[list([1, 2, 3]),list([0, 2]),list([0, 1, 3]),list([0, 2])]]
```

**Output**

- answer = `True`

**Explanation**

One odd length cycle would be `0 -> 2 -> 1 -> 0`

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Detecting-an-Odd-Length-Cycle.py"></script>
