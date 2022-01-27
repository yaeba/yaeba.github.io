---
title: "Sum of Two Numbers with Sorted List"
tags: ["two pointers", "array"]
---

Given a list of integers `nums` sorted in ascending order and an integer `k`, return whether any two elements from the list add up to `k`. You may **not** use the same element twice.

Note: Numbers can be negative or 0.

This should be done in $$\mathcal{O}(1)$$ space.

**Constraints**

- `n ≤ 100,000` where `n` is the length of `nums`

[https://binarysearch.com/problems/Sum-of-Two-Numbers-with-Sorted-List](https://binarysearch.com/problems/Sum-of-Two-Numbers-with-Sorted-List){:target="\_blank"}

## Examples

### Example 1

**Input**

- nums = `[1, 3, 5, 8]`
- k = `6`

**Output**

- answer = `True`

**Explanation**

We can have `1 + 5 = 6`.

### Example 2

**Input**

- nums = `[1, 3, 5, 8]`
- k = `7`

**Output**

- answer = `False`

**Explanation**

There's no two numbers that add up to `7`.

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Sum-of-Two-Numbers-with-Sorted-List.cpp"></script>
