---
title: "Minimum Initial Value for Positive Prefix Sums"
tags: ["array", "prefix sum"]
---

You are given a list of integers `nums`. Return the minimum positive value we can append to the beginning of `nums` such that prefix sums of the resulting list contains numbers that are all greater than `0`.

**Constraints**

- `n ≤ 100,000` where `n` is the length of `nums`

[https://binarysearch.com/problems/Minimum-Initial-Value-for-Positive-Prefix-Sums](https://binarysearch.com/problems/Minimum-Initial-Value-for-Positive-Prefix-Sums){:target="\_blank"}

## Examples

### Example 1

**Input**

- nums = `[2, -5, 3, 2]`

**Output**

- answer = `4`

**Explanation**

If we have append `4` to the list then we have `[4, 2, -5, 3, 2]`.

The prefix sums are then `[4, 6, 1, 4, 6]`, all of which are `> 0`.

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Minimum-Initial-Value-for-Positive-Prefix-Sums.cpp"></script>
