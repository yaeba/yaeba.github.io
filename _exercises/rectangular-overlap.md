---
title: "Rectangular Overlap"
---

You are given two lists of integers `rect0` and `rect1` representing coordinates `(x0, y0, x1, y1)` of two rectangles. `(x0, y0)` is the bottom left coordinate and `(x1, y1)` is the upper right coordinate.

Return whether the two rectangles overlap.

Note: if two rectangles touch only in their perimeters, they don't overlap.

[https://binarysearch.com/problems/Rectangular-Overlap](https://binarysearch.com/problems/Rectangular-Overlap){:target="\_blank"}

## Examples

### Example 1

**Input**

- rect0 = `[0, 0, 10, 10]`
- rect1 = `[5, 5, 30, 30]`

**Output**

- answer = `True`

**Explanation**

### Example 2

**Input**

- rect0 = `[0, 0, 10, 10]`
- rect1 = `[10, 10, 30, 30]`

**Output**

- answer = `False`

**Explanation**

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Rectangular-Overlap.py"></script>
