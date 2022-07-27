---
title: "Lexicographically Smallest Non-Palindromic String"
tags: ["greedy", "string"]
---

You are given a lowercase alphabet string `s` that is a palindrome. Update one character such that `s` is no longer a palindrome and is lexicographically smallest.

**Constraints**

- `2 ≤ n ≤ 100,000` where `n` is the length of `s`

[https://binarysearch.com/problems/Lexicographically-Smallest-Non-Palindromic-String](https://binarysearch.com/problems/Lexicographically-Smallest-Non-Palindromic-String){:target="\_blank"}

## Examples

### Example 1

**Input**

- s = `racecar`

**Output**

- answer = `aacecar`

**Explanation**

We can change the first `"r"` to `"a"` to get the lexicographically smallest string that is not a palindrome.

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Lexicographically-Smallest-Non-Palindromic-String.cpp"></script>
