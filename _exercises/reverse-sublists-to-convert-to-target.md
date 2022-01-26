---
title: "Reverse Sublists to Convert to Target"
---

Given two lists of integers `nums`, and `target`, consider an operation where you take some sublist in `nums` and reverse it. Return whether it's possible to turn `nums` into `target`, given you can make any number of operations.

**Constraints**

- `0 ≤ n ≤ 100,000` where `n` is the length of `nums`
- `0 ≤ m ≤ 100,000` where `m` is the length of `target`

[https://binarysearch.com/problems/Reverse-Sublists-to-Convert-to-Target](https://binarysearch.com/problems/Reverse-Sublists-to-Convert-to-Target){:target="\_blank"}

## Examples

### Example 1

**Input**

- nums = `[1, 2, 3, 8, 9]`
- target = `[3, 2, 1, 9, 8]`

**Output**

- answer = `True`

**Explanation**

We can reverse `[1, 2, 3]` and `[8, 9]`

### Example 2

**Input**

- nums = `[10, 2, 3, 8, 9]`
- target = `[3, 2, 1, 9, 8]`

**Output**

- answer = `False`

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Reverse-Sublists-to-Convert-to-Target.py"></script>
