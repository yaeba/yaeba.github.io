---
title: "Longest Interval"
tags: ["greedy"]
---

You are given a two-dimensional list of integers `intervals` where each list represents an inclusive `[start, end]` interval. Return the longest interval that you can make by merging any number of intersecting intervals.

**Constraints**

- `n ≤ 100,000` where `n` is the length of `intervals`

[https://binarysearch.com/problems/Longest-Interval](https://binarysearch.com/problems/Longest-Interval){:target="\_blank"}

## Examples

### Example 1

**Input**

- intervals =

```
[[ 1, 5],
 [ 3, 8],
 [ 4, 5],
 [10,13],
 [15,17]]
```

**Output**

- answer = `8`

**Explanation**

After merging, we have the interval `[1, 8]` which has a length of 8

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Longest-Interval.py"></script>
