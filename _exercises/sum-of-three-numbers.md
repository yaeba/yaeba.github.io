---
title: "Sum of Three Numbers"
tags: ["two pointers", "hash table", "array"]
---

Given a list of integers `nums` and an integer `k`, determine if there are three distinct elements in the list that add up to `k`.

**Constraints**

- `n ≤ 1,000` where `n` is the length of `nums`
- `k ≤ 1,000`

[https://binarysearch.com/problems/Sum-of-Three-Numbers](https://binarysearch.com/problems/Sum-of-Three-Numbers){:target="\_blank"}

## Examples

### Example 1

**Input**

- nums = `[4, 1, 1, 3]`
- k = `5`

**Output**

- answer = `True`

**Explanation**

We can pick 3, 1, and 1 to get 5.

### Example 2

**Input**

- nums = `[4, 1, 2, 3]`
- k = `5`

**Output**

- answer = `False`

**Explanation**

We can't pick any 3 of these numbers to make 5.

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Sum-of-Three-Numbers.java"></script>
