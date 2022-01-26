---
title: "Interval Intersection"
tags: ["greedy"]
---

Given a two-dimensional integer list `intervals` of the form `[start, end]` representing intervals (inclusive), return their intersection, that is, the interval that lies within all of the given intervals.

You can assume that the intersection will be non-empty.

**Constraints**

- `1 ≤ n ≤ 100,000` where `n` is the length of `intervals`

[https://binarysearch.com/problems/Interval-Intersection](https://binarysearch.com/problems/Interval-Intersection){:target="\_blank"}

## Examples

### Example 1

**Input**

- intervals = `[[1, 100], [10, 50], [15, 65]]`

**Output**

- answer = `[15, 50]`

**Explanation**

Consider the ranges [1, 100], [10, 50], [15, 65] on a line. The range [15, 50] is the only interval that is included by all of them.

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Interval-Intersection.java"></script>
