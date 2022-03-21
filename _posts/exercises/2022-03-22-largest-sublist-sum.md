---
title: "Largest Sublist Sum"
tags: ["divide and conquer", "greedy", "prefix sum"]
---

Given a list of integers `nums`, return the sum of a non-empty contiguous sublist with the largest sum.

**Constraints**

- `1 ≤ n ≤ 100,000` where `n` is the length of `nums`

[https://binarysearch.com/problems/Largest-Sublist-Sum](https://binarysearch.com/problems/Largest-Sublist-Sum){:target="\_blank"}

## Examples

### Example 1

**Input**

- nums = `[3, 4, -2, 5]`

**Output**

- answer = `10`

**Explanation**

We can take the whole list and its sum is `3 + 4 - 2 + 5 = 10`

### Example 2

**Input**

- nums = `[10, -5, 12, -100, 3, -1, 20]`

**Output**

- answer = `22`

**Explanation**

`[3, -1, 20]` is the contiguous sublist with the largest sum.

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Largest-Sublist-Sum.cpp"></script>
