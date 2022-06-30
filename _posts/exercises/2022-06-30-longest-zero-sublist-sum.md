---
title: "Longest Zero Sublist Sum"
tags: ["dynamic programming", "prefix sum"]
---

Given a list of integers `nums`, which contains either `-1` or `1`, return the length of the longest sublist that sums to `0`.

**Constraints**

- `n ≤ 100,000` where `n` is the length of `nums`.

[https://binarysearch.com/problems/Longest-Zero-Sublist-Sum](https://binarysearch.com/problems/Longest-Zero-Sublist-Sum){:target="\_blank"}

## Examples

### Example 1

**Input**

- nums = `[1, 1, 1, 1, -1, -1, 1, -1]`

**Output**

- answer = `6`

**Explanation**

The longest sublist that sums to 0 is [1, 1, -1, -1, 1, -1] which has length 6.

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Longest-Zero-Sublist-Sum.py"></script>
