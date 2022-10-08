---
title: "Longest Arithmetic Subsequence with Difference Constraint"
tags: ["math", "dynamic programming"]
---

Given a list of integers `nums` and an integer `diff`, return the length of the longest arithmetic subsequence where the difference between each consecutive numbers in the subsequence is `diff`.

**Constraints**

- `0 ≤ n ≤ 100,000` where `n` is the length of `nums`

[https://binarysearch.com/problems/Longest-Arithmetic-Subsequence-with-Difference-Constraint](https://binarysearch.com/problems/Longest-Arithmetic-Subsequence-with-Difference-Constraint){:target="\_blank"}

## Examples

### Example 1

**Input**

- nums = `[-2, 0, 3, 6, 1, 9]`
- diff = `3`

**Output**

- answer = `4`

**Explanation**

We can pick the subsequence `[0, 3, 6, 9]`.

### Example 2

**Input**

- nums = `[9, 8, 7, 5, 3]`
- diff = `-2`

**Output**

- answer = `4`

**Explanation**

We can pick the subsequence `[9, 7, 5, 3]`.

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Longest-Arithmetic-Subsequence-with-Difference-Constraint.py"></script>
