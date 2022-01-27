---
title: "Longest Interval Containing One Number"
---

You are given a list of unique integers `nums`. Return the size of the largest inclusive interval `[start, end]` such that it contains exactly one number in `nums`.

**Constraints**

- `1 ≤ n ≤ 100,000` where `n` is the length of `nums`
- `1 ≤ start ≤ end ≤ 100,000`

[https://binarysearch.com/problems/Longest-Interval-Containing-One-Number](https://binarysearch.com/problems/Longest-Interval-Containing-One-Number){:target="\_blank"}

## Examples

### Example 1

**Input**

- nums = `[10, 5, 19]`

**Output**

- answer = `99990`

**Explanation**

The largest interval that contains one number is `[11, 100000]` which contains `19`.

### Example 2

**Input**

- nums = `[5, 50000, 90000]`

**Output**

- answer = `89994`

**Explanation**

The largest interval that contains one number is `[6, 89999]` which contains `50,000`.

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Longest-Interval-Containing-One-Number.cpp"></script>
