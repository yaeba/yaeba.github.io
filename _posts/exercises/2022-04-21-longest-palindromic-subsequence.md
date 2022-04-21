---
title: "Longest Palindromic Subsequence"
tags: ["string", "dynamic programming"]
---

Given a string `s` with all lower case characters, find the length of the longest palindromic subsequence in `s`.

**Constraints**

- `n ≤ 1,000` where `n` is the length of `s`

[https://binarysearch.com/problems/Longest-Palindromic-Subsequence](https://binarysearch.com/problems/Longest-Palindromic-Subsequence){:target="\_blank"}

## Examples

### Example 1

**Input**

- s = `bbbbbbbbbb`

**Output**

- answer = `10`

**Explanation**

The whole string is a palindrome.

### Example 2

**Input**

- s = `a`

**Output**

- answer = `1`

### Example 3

**Input**

- s = `binarysearch`

**Output**

- answer = `3`

**Explanation**

The longest palindromic subsequence here is **aea**.

### Example 4

**Input**

- s = `rbaicneacrayr`

**Output**

- answer = `7`

**Explanation**

`racecar` is the longest palindromic subsequence of **r**b**a**i**c**n**e**a**c**r**a**y**r**

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Longest-Palindromic-Subsequence.cpp"></script>
<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Longest-Palindromic-Subsequence.py"></script>
