---
title: "Split String Into K Palindromes"
tags: ["dynamic programming", "string"]
---

Given a lowercase alphabet string `s` and an integer `k`, you want to divide the string into `k` disjoint parts such that each part is a palindrome. Return the minimum number of characters that need to be changed such that this is possible.

**Constraints**

- `k ≤ n ≤ 100` where `n` is the length of `s`

[https://binarysearch.com/problems/Split-String-Into-K-Palindromes](https://binarysearch.com/problems/Split-String-Into-K-Palindromes){:target="\_blank"}

## Examples

### Example 1

**Input**

- s = `abcadfe`
- k = `2`

**Output**

- answer = `2`

**Explanation**

If we update `"c"` to `"b"` and the `"e"` to `"d", then we can divide the string into `["abba", "dfd"]`, both of which is a palindrome.

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Split-String-Into-K-Palindromes.py"></script>
