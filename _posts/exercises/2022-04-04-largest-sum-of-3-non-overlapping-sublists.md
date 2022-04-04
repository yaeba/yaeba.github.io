---
title: "Largest Sum of 3 Non-Overlapping Sublists"
tags: ["prefix sum"]
---

Given a list of integers `nums` and an integer `k`, return the largest sum of three non-overlapping sublists of `nums` each of size `k`.

**Constraints**

- `n ≤ 100,000` where `n` is the length of `nums`.

[https://binarysearch.com/problems/Largest-Sum-of-3-Non-Overlapping-Sublists](https://binarysearch.com/problems/Largest-Sum-of-3-Non-Overlapping-Sublists){:target="\_blank"}

## Examples

### Example 1

**Input**

- nums = `[1, 1, 1, -5, 3, 3, 3, -7, 2, 2, 2]`
- k = `3`

**Output**

- answer = `18`

**Explanation**

We can pick the following sublists `[1, 1, 1]`, `[3, 3, 3]`, and `[2, 2, 2]`.

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Largest-Sum-of-3-Non-Overlapping-Sublists.py"></script>
