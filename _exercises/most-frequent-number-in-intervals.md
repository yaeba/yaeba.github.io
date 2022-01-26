---
title: "Most Frequent Number in Intervals"
tags: ["line sweep"]
---

You are given a list of list of integers `intervals` where each element contains the inclusive interval `[start, end]`.

Return the most frequently occurring number in the intervals. If there are ties, return the smallest number.

**Constraints**

- `n ≤ 100,000` where `n` is the length of `intervals`

[https://binarysearch.com/problems/Most-Frequent-Number-in-Intervals](https://binarysearch.com/problems/Most-Frequent-Number-in-Intervals){:target="\_blank"}

## Examples

### Example 1

**Input**

- intervals = `[[1, 4], [3, 5], [6, 9], [7, 9]]`

**Output**

- answer = `3`

**Explanation**

The most frequent numbers are `[3, 4, 7, 8, 9]` and they all occur twice but `3` is the smallest one.

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Most-Frequent-Number-in-Intervals.py"></script>
