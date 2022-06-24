---
title: "Sum Pairs to Target"
tags: ["two pointers", "array", "hash table"]
---

You are given a list of integers `nums` and an integer `target`. In one operation we can remove any two numbers in `nums` if the pair sums to `target`. Return the maximum number of operations we can perform.

**Constraints**

- `n ≤ 100,000` where `n` is the length of `nums`

[https://binarysearch.com/problems/Sum-Pairs-to-Target](https://binarysearch.com/problems/Sum-Pairs-to-Target){:target="\_blank"}

## Examples

### Example 1

**Input**

- nums = `[1, 3, 5, 3, 7]`
- target = `6`

**Output**

- answer = `2`

**Explanation**

We can pair `[1, 5]` and `[3, 3]`.

### Example 2

**Input**

- nums = `[6]`
- target = `6`

**Output**

- answer = `0`

**Explanation**

There's no two numbers that sum to `6`

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Sum-Pairs-to-Target.cpp"></script>
