---
title: "Arithmetic Sequence Permutation"
tags: ["array"]
---

Given a list of integers `nums`, return whether you can rearrange the order of `nums` such that the difference between every consecutive two numbers is the same.

**Constraints**

- `n ≤ 100,000` where `n` is the length of `nums`

[https://binarysearch.com/problems/Arithmetic-Sequence-Permutation](https://binarysearch.com/problems/Arithmetic-Sequence-Permutation){:target="\_blank"}

## Examples

### Example 1

**Input**

- nums = `[1, 5, 1, 5, 1, 5]`

**Output**

- answer = `False`

**Explanation**

The difference between every consecutive two numbers alternates between `4` and `-4`.

### Example 2

**Input**

- nums = `[7, 1, 5, 3]`

**Output**

- answer = `True`

**Explanation**

If we rearrange `nums` to `[1, 3, 5, 7]`, then the difference between every two consecutive numbers is `2`.

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Arithmetic-Sequence-Permutation.py"></script>
