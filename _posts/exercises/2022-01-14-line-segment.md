---
title: "Line Segment"
tags: ["math"]
---

Given a list of `[x, y]` coordinates in a Cartesian plane, return whether the coordinates form a straight line segment.

**Constraints**

- `n ≤ 100,000` where `n` is the length of `coordinates`.

[https://binarysearch.com/problems/Line-Segment](https://binarysearch.com/problems/Line-Segment){:target="\_blank"}

## Examples

### Example 1

**Input**

- coordinates = `[[1, 1], [3, 3], [7, 7]]`

**Output**

- answer = `True`

**Explanation**

This forms a line segment with a slope 1

### Example 2

**Input**

- coordinates = `[[1, 1], [3, 3], [4, 6]]`

**Output**

- answer = `False`

**Explanation**

The `3` points don't form a line segment, since the slope between `[1, 1]` and `[3, 3]` is `1` but the slope between `[3, 3]` and `[4, 6]` is `3`.

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Line-Segment.py"></script>
