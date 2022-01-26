---
title: "K Prefix"
tags: ["prefix sum", "array"]
---

Given a list of integers `nums` and an integer `k`, return the maximum possible `i` where `nums[0] + nums[1] + ... + nums[i] ≤ k`. Return `-1` if no valid `i` exists.

**Constraints**

- `0 ≤ n ≤ 1,000` where `n` is the length of `nums`.
- `-1,000 ≤ nums[i] ≤ 1,000`
- `0 ≤ k ≤ 10 ** 9`

[https://binarysearch.com/problems/K-Prefix](https://binarysearch.com/problems/K-Prefix){:target="\_blank"}

## Examples

### Example 1

**Input**

- nums = `[3, -5, 4, 1, 6]`
- k = `4`

**Output**

- answer = `3`

**Explanation**

The largest `i` here is 3, since we have `nums[0] + ... + nums[3] = 3` and if we added the next number (6) the sum would no longer be less than `k`.

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=K-Prefix.cpp"></script>
