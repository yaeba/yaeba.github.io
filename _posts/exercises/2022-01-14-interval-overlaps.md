---
title: "Interval Overlaps"
tags: ["two pointers"]
---

You are given a list of closed intervals `l0` and another list of intervals `l1`. Individually, each list is non-overlapping and are sorted in ascending order.

Return the overlap of the two intervals sorted in ascending order.

**Constraints**

- `n ≤ 100,000` where `n` is the length of `l0`
- `m ≤ 100,000` where `m` is the length of `l1`

[https://binarysearch.com/problems/Interval-Overlaps](https://binarysearch.com/problems/Interval-Overlaps){:target="\_blank"}

## Examples

### Example 1

**Input**

- l0 = `[[1, 3], [5, 6], [7, 9]]`
- l1 = `[[1, 4], [5, 7]]`

**Output**

- answer = `[[1, 3], [5, 6], [7, 7]]`

### Example 2

**Input**

- l0 = `[[1, 3], [5, 6], [7, 9]]`
- l1 = `[[100, 200]]`

**Output**

- answer = `[]`

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Interval-Overlaps.py"></script>
