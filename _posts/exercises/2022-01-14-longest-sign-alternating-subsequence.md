---
title: "Longest Sign Alternating Subsequence"
tags: ["array"]
---

Given a list of non-zero integers `nums`, return the length of longest subsequence that flips signs on each consecutive number.

**Constraints**

- `n ≤ 100,000` where `n` is the length of `nums`.

[https://binarysearch.com/problems/Longest-Sign-Alternating-Subsequence](https://binarysearch.com/problems/Longest-Sign-Alternating-Subsequence){:target="\_blank"}

## Examples

### Example 1

**Input**

- nums = `[1, 2, -5, 3, -2]`

**Output**

- answer = `4`

**Explanation**

We can pick `[1, -5, 3, -2]`.

### Example 2

**Input**

- nums = `[-1, -2, 5, -3, 2]`

**Output**

- answer = `4`

**Explanation**

We can pick `[-1, 5, -3, 2]`

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Longest-Sign-Alternating-Subsequence.py"></script>
