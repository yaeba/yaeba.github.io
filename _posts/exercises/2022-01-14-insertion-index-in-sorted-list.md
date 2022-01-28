---
title: "Insertion Index in Sorted List"
tags: ["array", "binary search"]
---

Given a list of integers `nums`, sorted in ascending order, and a number `target`, return the index where `target` should be inserted to keep `nums` sorted. If `target` already exists in `nums`, return the largest index where `target` can be inserted.

This should be done in $$\mathcal{O}(\log n)$$.

**Constraints**

- `1 ≤ n ≤ 100,000` where `n` is the length of `nums`

[https://binarysearch.com/problems/Insertion-Index-in-Sorted-List](https://binarysearch.com/problems/Insertion-Index-in-Sorted-List){:target="\_blank"}

## Examples

### Example 1

**Input**

- nums = `[1]`
- target = `0`

**Output**

- answer = `0`

### Example 2

**Input**

- nums = `[1, 2, 4, 5]`
- target = `3`

**Output**

- answer = `2`

### Example 3

**Input**

- nums = `[1, 1, 1, 2, 4, 5]`
- target = `1`

**Output**

- answer = `3`

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Insertion-Index-in-Sorted-List.java"></script>
