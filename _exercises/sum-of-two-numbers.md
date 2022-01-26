---
title: "Sum of Two Numbers"
tags: ["array", "hash table"]
---

Given a list of numbers `nums` and a number `k`, return whether any two elements from the list add up to `k`. You may **not** use the same element twice.

Note: Numbers can be negative or 0.

**Constraints**

- `n ≤ 100,000` where `n` is the length of `nums`

[https://binarysearch.com/problems/Sum-of-Two-Numbers](https://binarysearch.com/problems/Sum-of-Two-Numbers){:target="\_blank"}

## Examples

### Example 1

**Input**

- nums = `[35, 8, 18, 3, 22]`
- k = `11`

**Output**

- answer = `True`

**Explanation**

8 + 3 = 11

### Example 2

**Input**

- nums = `[10, 36, 22, 14]`
- k = `4`

**Output**

- answer = `False`

**Explanation**

No two numbers in this list add up to 4.

### Example 3

**Input**

- nums = `[24, 10, 11, 4]`
- k = `15`

**Output**

- answer = `True`

**Explanation**

11 + 4 = 15

### Example 4

**Input**

- nums = `[-22, 22, -11, 11]`
- k = `0`

**Output**

- answer = `True`

**Explanation**

-11 + 11 = 0

### Example 5

**Input**

- nums = `[15, 0, 3, 2]`
- k = `15`

**Output**

- answer = `True`

**Explanation**

15 + 0 = 15

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Sum-of-Two-Numbers.cpp"></script>