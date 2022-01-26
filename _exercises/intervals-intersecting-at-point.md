---
title: "Intervals Intersecting at Point"
---

You are given a two-dimensional list of integers `intervals` and an integer `point`. Each element contains `[start, end]` represents an inclusive interval.

Return the number of intervals that are intersecting at `point`.

**Constraints**

- `n ≤ 100,000` where `n` is the length of `intervals`

[https://binarysearch.com/problems/Intervals-Intersecting-at-Point](https://binarysearch.com/problems/Intervals-Intersecting-at-Point){:target="\_blank"}

## Examples

### Example 1

**Input**

- intervals = `[[1, 5], [3, 9], [4, 8], [10, 13]]`
- point = `4`

**Output**

- answer = `3`

**Explanation**

At time `4`, there are `3` intervals that are intersecting: `[1, 5], [3, 9], [4, 8]`

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Intervals-Intersecting-at-Point.py"></script>
