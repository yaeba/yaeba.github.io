---
title: "Anagram Substrings"
tags: ["hash table", "string"]
---

Given two strings `s0` and `s1`, return the number of substrings where `s1` contains any anagram of `s0`.

**Constraints**

- `n ≤ 100,000` where `n` is the length of `s0`
- `m ≤ 100,000` where `m` is the length of `s1`

[https://binarysearch.com/problems/Anagram-Substrings](https://binarysearch.com/problems/Anagram-Substrings){:target="\_blank"}

## Examples

### Example 1

**Input**

- s0 = `abc`
- s1 = `bcabxabc`

**Output**

- answer = `3`

**Explanation**

The substrings `"bca"`, `"cab"` and `"abc"` of `s0` are permutations of `"abc"`.

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Anagram-Substrings.py"></script>
