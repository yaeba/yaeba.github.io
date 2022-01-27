---
title: "Longest Common Subsequence"
tags: ["dynamic programming"]
---

Given two strings `a` and `b`, return the length of their longest common subsequence.

**Constraints**

- `n ≤ 1,000` where `n` is the length of `a`
- `m ≤ 1,000` where `m` is the length of `b`

[https://binarysearch.com/problems/Longest-Common-Subsequence](https://binarysearch.com/problems/Longest-Common-Subsequence){:target="\_blank"}

## Examples

### Example 1

**Input**

- a = `abcvc`
- b = `bv`

**Output**

- answer = `2`

**Explanation**

`bv` is the longest common subsequence.

### Example 2

**Input**

- a = `abc`
- b = `abc`

**Output**

- answer = `3`

**Explanation**

### Example 3

**Input**

- a = `abc`
- b = `def`

**Output**

- answer = `0`

**Explanation**

### Example 4

**Input**

- a = `binarysearch`
- b = `searchbinary`

**Output**

- answer = `6`

**Explanation**

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Longest-Common-Subsequence.cpp"></script>
