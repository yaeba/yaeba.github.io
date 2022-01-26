---
title: "Mixed Sorting"
tags: ["array"]
---

Given a list of integers `nums`, sort the array such that:

- All even numbers are sorted in increasing order
- All odd numbers are sorted in decreasing order
- The relative positions of the even and odd numbers remain the same

**Constraints**

- `n ≤ 100,000` where `n` is the length of `nums`

[https://binarysearch.com/problems/Mixed-Sorting](https://binarysearch.com/problems/Mixed-Sorting){:target="\_blank"}

## Examples

### Example 1

**Input**

- nums = `[8, 13, 11, 90, -5, 4]`

**Output**

- answer = `[4, 13, 11, 8, -5, 90]`

**Explanation**

The even numbers are sorted in increasing order, the odd numbers are sorted in decreasing number, and the relative positions were [even, odd, odd, even, odd, even] and remain the same after sorting.

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Mixed-Sorting.cpp"></script>
<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Mixed-Sorting.py"></script>
