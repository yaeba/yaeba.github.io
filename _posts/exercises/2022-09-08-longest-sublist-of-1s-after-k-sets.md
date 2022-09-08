---
title: "Longest Sublist of 1s After K Sets"
tags: ["two pointers", "array"]
---

You are given a list of integers `nums` containing `1`s and `0`s and an integer `k`. Given that you can set at most `k` `0`s to `1`s, return the length of the longest sublist containing all `1`s.

**Constraints**

- `n ≤ 100,000` where `n` is the length of `nums`

[https://binarysearch.com/problems/Longest-Sublist-of-1s-After-K-Sets](https://binarysearch.com/problems/Longest-Sublist-of-1s-After-K-Sets){:target="\_blank"}

## Examples

### Example 1

**Input**

- nums = `[1, 1, 1, 0, 0, 1, 0]`
- k = `2`

**Output**

- answer = `6`

**Explanation**

We can set the two middle `0`s to `1`s and then the list becomes `[1, 1, 1, 1, 1, 1, 0]`.

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Longest-Sublist-of-1s-After-K-Sets.cpp"></script>
