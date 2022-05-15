---
title: "K Distinct Window"
tags: ["two pointers", "array"]
---

Given a list of integers `nums` and an integer `k`, return a list of count of distinct numbers in each window of size `k`.

**Constraints**

- `1 ≤ k ≤ n ≤ 100,000` where `n` is length of `nums`.

[https://binarysearch.com/problems/K-Distinct-Window](https://binarysearch.com/problems/K-Distinct-Window){:target="\_blank"}

## Examples

### Example 1

**Input**

- nums = `[1, 1, 2, 2, 3]`
- k = `2`

**Output**

- answer = `[1, 2, 1, 2]`

**Explanation**

The windows are `[1, 1]`, `[1, 2]`, `[2, 2]`, and `[2, 3]`.

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=K-Distinct-Window.py"></script>
