---
title: "Minimize Amplitude After Deleting K-Length Sublist 🎄"
tags: ["prefix sum", "array"]
---

You are given a list of integers `nums` and an integer `k`. Given that you must first remove a sublist of length `k`, return the minimum resulting `max(nums) - min(nums)`.

**Constraints**

- `0 ≤ k < n ≤ 100,000` where `n` is the length of `nums`

[https://binarysearch.com/problems/Minimize-Amplitude-After-Deleting-K-Length-Sublist](https://binarysearch.com/problems/Minimize-Amplitude-After-Deleting-K-Length-Sublist){:target="\_blank"}

## Examples

### Example 1

**Input**

- nums = `[1, 2, 9, 8, 7, 3]`
- k = `3`

**Output**

- answer = `2`

**Explanation**

We can remove `[9, 8, 7]` to get `[1, 2, 3]` and `3 - 1 = 2`

### Example 2

**Input**

- nums = `[5, 1, 2]`
- k = `0`

**Output**

- answer = `4`

**Explanation**

We can't remove a sublist since `k = 0`, so we just return the current amplitude which is `5 - 1`.

### Example 3

**Input**

- nums = `[2, 1, 4, 7, 8]`
- k = `2`

**Output**

- answer = `3`

**Explanation**

We can remove `[7, 8]` to get `[2, 1, 4]` and `4 - 1 = 3`

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Minimize-Amplitude-After-Deleting-K-Length-Sublist.py"></script>
