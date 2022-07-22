---
title: "Maximum Absolute Value of Sublist"
tags: ["greedy"]
---

You are given a list of integers `nums`. Return the maximum possible `abs(nums[i] + nums[i + 1] + ... + nums[j])` for any `i <= j`.

**Constraints**

- `0 ≤ n ≤ 100,000` where `n` is the length of `nums`

[https://binarysearch.com/problems/Maximum-Absolute-Value-of-Sublist](https://binarysearch.com/problems/Maximum-Absolute-Value-of-Sublist){:target="\_blank"}

## Examples

### Example 1

**Input**

- nums = `[5, -7, -2, 4]`

**Output**

- answer = `9`

**Explanation**

We can take the sublist `[-7, -2]` to get `abs(-7 + -2) = 9`.

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Maximum-Absolute-Value-of-Sublist.cpp"></script>
