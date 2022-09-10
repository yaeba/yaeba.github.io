---
title: "Maximum Sum Removing K Numbers From Ends"
tags: ["prefix sum", "array"]
---

You are given a list of integers `nums` and integer `k`. Return the maximum sum of elements that you can remove given that you must pop exactly `k` times, where each pop can be from the left or the right end.

**Constraints**

- `k ≤ n ≤ 100,000` where `n` is length of `nums`.

[https://binarysearch.com/problems/Maximum-Sum-Removing-K-Numbers-From-Ends](https://binarysearch.com/problems/Maximum-Sum-Removing-K-Numbers-From-Ends){:target="\_blank"}

## Examples

### Example 1

**Input**

- nums = `[1, 3, 4, 2, 0]`
- k = `2`

**Output**

- answer = `4`

**Explanation**

We take the `1` and the `3`

### Example 2

**Input**

- nums = `[3, 1, 1, 1, 13, -1, 0]`
- k = `4`

**Output**

- answer = `15`

**Explanation**

We take `3` from the left and `0`, `-1`, `13` from the right.

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Maximum-Sum-Removing-K-Numbers-From-Ends.cpp"></script>
