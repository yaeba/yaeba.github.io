---
title: "Number of Sublists With Sum of Target"
tags: ["hash table", "prefix sum", "array"]
---

Given a list of integers `nums` and an integer `target`, return the number of sublists whose sum is equal to `target`.

**Constraints**

- `n ≤ 100,000` where `n` is the length of `nums`

[https://binarysearch.com/problems/Number-of-Sublists-With-Sum-of-Target](https://binarysearch.com/problems/Number-of-Sublists-With-Sum-of-Target){:target="\_blank"}

## Examples

### Example 1

**Input**

- nums = `[2, 0, 2]`
- target = `2`

**Output**

- answer = `4`

**Explanation**

We have these sublists whose sum is `2`: `[2]`, `[2, 0]`, `[0, 2]`, `[2]`

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Number-of-Sublists-With-Sum-of-Target.py"></script>
