---
title: "Sum of Four Numbers"
tags: ["two pointers", "hash table"]
---

Given a list of integers `nums` and an integer `k`, return whether there are four distinct elements in the list that add up to `k`.

**Constraints**

- `n ≤ 100` where `n` is length of `nums`.

[https://binarysearch.com/problems/Sum-of-Four-Numbers](https://binarysearch.com/problems/Sum-of-Four-Numbers){:target="\_blank"}

## Examples

### Example 1

**Input**

- nums = `[10, 3, 5, 9, 4, 0]`
- k = `17`

**Output**

- answer = `True`

**Explanation**

We can use `[10, 3, 4, 0]` to get `17`

### Example 2

**Input**

- nums = `[2]`
- k = `8`

**Output**

- answer = `False`

**Explanation**

There's no `4` numbers that sum up to `2`.

### Example 3

**Input**

- nums = `[2, 2, 2, 2]`
- k = `8`

**Output**

- answer = `True`

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Sum-of-Four-Numbers.py"></script>
