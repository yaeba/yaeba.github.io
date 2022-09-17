---
title: "Sum of Three Numbers Less than Target"
tags: ["array", "two pointers"]
---

Given a list of integers `nums` and an integer `target`, return the number of triples `i < j < k` that exist such that `nums[i] + nums[j] + nums[k] < target`.

**Constraints**

- `n ≤ 1,000` where `n` is the length of `nums`

[https://binarysearch.com/problems/Sum-of-Three-Numbers-Less-than-Target](https://binarysearch.com/problems/Sum-of-Three-Numbers-Less-than-Target){:target="\_blank"}

## Examples

### Example 1

**Input**

- nums = `[-3, 5, 3, 2, 7]`
- target = `9`

**Output**

- answer = `5`

**Explanation**

Here are the different triples' values:

- `-3 + 5 + 3 = 5`
- `-3 + 5 + 2 = 4`
- `-3 + 3 + 2 = 2`
- `-3 + 3 + 7 = 7`
- `-3 + 2 + 7 = 6`

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Sum-of-Three-Numbers-Less-than-Target.java"></script>
