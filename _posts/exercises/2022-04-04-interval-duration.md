---
title: "Interval Duration"
tags: ["greedy"]
---

You are given a two-dimensional list of integers `intervals` where each list represents an inclusive `[start, end]` interval.

Return the total unique duration it covers.

**Constraints**

- `n ≤ 100,000` where `n` is length of `intervals`.

[https://binarysearch.com/problems/Interval-Duration](https://binarysearch.com/problems/Interval-Duration){:target="\_blank"}

## Examples

### Example 1

**Input**

- intervals =

```
[[45,60],
 [ 1, 5],
 [ 5,15],
 [ 2, 3]]
```

**Output**

- answer = `31`

**Explanation**

The total unique covered distance is `[45, 60]` (duration of `16`) and `[1 ,15]` (duration of `15`).

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Interval-Duration.py"></script>
