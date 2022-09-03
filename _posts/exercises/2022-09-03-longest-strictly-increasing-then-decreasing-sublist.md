---
title: "Longest Strictly Increasing Then Decreasing Sublist"
tags: ["two pointers", "array"]
---

You are given a list of integers `nums`. Return the length of the longest sublist such that its length is at least `3` and its values are strictly increasing and then decreasing. Both the increasing part and the decreasing part must be non-empty.

**Constraints**

- `n ≤ 100,000` where `n` is the length of `nums`

[https://binarysearch.com/problems/Longest-Strictly-Increasing-Then-Decreasing-Sublist](https://binarysearch.com/problems/Longest-Strictly-Increasing-Then-Decreasing-Sublist){:target="\_blank"}

## Examples

### Example 1

**Input**

- nums = `[7, 1, 3, 5, 2, 0]`

**Output**

- answer = `5`

**Explanation**

The sublist `[1, 3, 5, 2, 0]` is strictly increasing then decreasing.

### Example 2

**Input**

- nums = `[1, 2, 3]`

**Output**

- answer = `0`

### Example 3

**Input**

- nums = `[3, 2, 1]`

**Output**

- answer = `0`

### Example 4

**Input**

- nums = `[1, 2, 1, 1]`

**Output**

- answer = `3`

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Longest-Strictly-Increasing-Then-Decreasing-Sublist.py"></script>
