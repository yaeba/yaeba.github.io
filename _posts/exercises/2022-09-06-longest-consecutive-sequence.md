---
title: "Longest Consecutive Sequence"
tags: ["array", "hash table"]
---

Given an unsorted array of integers `nums`, find the length of the longest sequence of consecutive elements.

**Constraints**

- `n ≤ 100,000` where `n` is the length of `nums`

[https://binarysearch.com/problems/Longest-Consecutive-Sequence](https://binarysearch.com/problems/Longest-Consecutive-Sequence){:target="\_blank"}

## Examples

### Example 1

**Input**

- nums = `[100, 4, 200, 1, 3, 2, 101, 105, 103, 102, 104]`

**Output**

- answer = `6`

**Explanation**

The longest sequence of consecutive elements is `[100, 101, 102, 103, 104, 105]`. so we return its length: `6`.

### Example 2

**Input**

- nums = `[100, 4, 200, 1, 3, 2]`

**Output**

- answer = `4`

**Explanation**

The longest sequence of consecutive elements is `[1, 2, 3, 4]`. so we return its length: `4`.

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Longest-Consecutive-Sequence.py"></script>
