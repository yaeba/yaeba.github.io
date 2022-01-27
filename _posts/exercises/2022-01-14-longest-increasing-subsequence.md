---
title: "Longest Increasing Subsequence"
tags: ["dynamic programming"]
---

Given an unsorted list of integers `nums`, return the longest strictly increasing subsequence of the array.

Bonus: Can you solve it in $$\mathcal{O}(n \log n)$$ time?

**Constraints**

- `n ≤ 1,000` where `n` is the length of `nums`

[https://binarysearch.com/problems/Longest-Increasing-Subsequence](https://binarysearch.com/problems/Longest-Increasing-Subsequence){:target="\_blank"}

## Examples

### Example 1

**Input**

- nums = `[6, 1, 7, 2, 8, 3, 4, 5]`

**Output**

- answer = `5`

**Explanation**

Longest increasing subsequence would be `[1, 2, 3, 4, 5]`

### Example 2

**Input**

- nums = `[12, 5, 6, 25, 8, 11, 10]`

**Output**

- answer = `4`

**Explanation**

One longest increasing subsequence would be `[5, 6, 8, 11]`

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Longest-Increasing-Subsequence.cpp"></script>
