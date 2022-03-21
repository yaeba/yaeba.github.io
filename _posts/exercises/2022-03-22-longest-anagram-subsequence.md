---
title: "Longest Anagram Subsequence"
tags: ["string"]
---

Given two lowercase alphabet strings `a` and `b`, return the length of the longest anagram subsequence.

**Constraints**

- `n ≤ 100,000` where `n` is the length of `a`
- `m ≤ 100,000` where `m` is the length of `b`

[https://binarysearch.com/problems/Longest-Anagram-Subsequence](https://binarysearch.com/problems/Longest-Anagram-Subsequence){:target="\_blank"}

## Examples

### Example 1

**Input**

- a = `afbc`
- b = `cxba`

**Output**

- answer = `3`

**Explanation**

- "abc" is a subsequence in "afbc"
- "cba" is a subsequence in "cxba"

And abc and cba are anagrams of each other.

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Longest-Anagram-Subsequence.cpp"></script>
<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Longest-Anagram-Subsequence.py"></script>
