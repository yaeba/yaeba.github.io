---
title: "Longest Sublist with K Distinct Numbers"
tags: ["array"]
---

Given an integer `k` and a list of integers `nums`, return the length of the longest sublist that contains at most `k` distinct integers.

**Constraints**

- `0 ≤ k ≤ n ≤ 100,000` where `n` is the length of `nums`

[https://binarysearch.com/problems/Longest-Sublist-with-K-Distinct-Numbers](https://binarysearch.com/problems/Longest-Sublist-with-K-Distinct-Numbers){:target="\_blank"}

## Examples

### Example 1

**Input**

- k = `1`
- nums = `[0, 0, 0, 0, 0]`

**Output**

- answer = `5`

### Example 2

**Input**

- k = `2`
- nums = `[0, 1, 2, 1, 0]`

**Output**

- answer = `3`

**Explanation**

The longest substring with `2` distinct integers is `[1,2,1]`, which has length of `3`.

### Example 3

**Input**

- k = `1`
- nums = `[0, 1, 2, 3, 4]`

**Output**

- answer = `1`

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Longest-Sublist-with-K-Distinct-Numbers.py"></script>
