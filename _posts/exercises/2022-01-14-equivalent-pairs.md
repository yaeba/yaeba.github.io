---
title: "Equivalent Pairs"
tags: ["hash table", "array"]
---

You are given a list of integers `nums`. Return the number of pairs `i < j` such that `nums[i] = nums[j]`.

**Constraints**

- `0 ≤ n ≤ 100,000` where `n` is the length of `nums`

[https://binarysearch.com/problems/Equivalent-Pairs](https://binarysearch.com/problems/Equivalent-Pairs){:target="\_blank"}

## Examples

### Example 1

**Input**

- nums = `[3, 2, 3, 2, 2]`

**Output**

- answer = `4`

**Explanation**

We have index pairs `(0, 2)`, `(1, 3)`, `(1, 4)`, `(3, 4)`.

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Equivalent-Pairs.py"></script>
