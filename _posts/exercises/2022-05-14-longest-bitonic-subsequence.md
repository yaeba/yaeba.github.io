---
title: "Longest Bitonic Subsequence"
tags: ["array"]
---

A sequence is called bitonic if it's strictly increasing and then strictly decreasing. A sequence that is only strictly increasing is bitonic. Also, a sequence that is only strictly decreasing is bitonic.

Given a list of integers `nums`, return the length of the longest bitonic subsequence.

**Constraints**

- `n ≤ 1,000` where `n` is the length of `nums`.

[https://binarysearch.com/problems/Longest-Bitonic-Subsequence](https://binarysearch.com/problems/Longest-Bitonic-Subsequence){:target="\_blank"}

## Examples

### Example 1

**Input**

- nums = `[1, 3, 2, 5, 9]`

**Output**

- answer = `4`

**Explanation**

`[1, 3, 5, 9]`

### Example 2

**Input**

- nums = `[10, 2, 5, 7, 3, 1]`

**Output**

- answer = `5`

**Explanation**

The longest bitonic subsequence is `[2, 5, 7, 3, 1]`

### Example 3

**Input**

- nums = `[1, 0, 3, 2, 9, 4, 5, 2]`

**Output**

- answer = `5`

**Explanation**

The longest bitonic subsequence is `[1, 3, 9, 5, 2]`

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Longest-Bitonic-Subsequence.cpp"></script>
