---
title: "Create Palindrome After Deleting at Most K Characters"
tags: ["dynamic programming"]
---

Given a string `s` and an integer `k` return whether you can delete at most `k` characters such that after the deletion `s` is a palindrome.

**Constraints**

- `n ≤ 1,000` where `n` is the length of `s`

[https://binarysearch.com/problems/Create-Palindrome-After-Deleting-at-Most-K-Characters](https://binarysearch.com/problems/Create-Palindrome-After-Deleting-at-Most-K-Characters){:target="\_blank"}

## Examples

### Example 1

**Input**

- s = `abcd`
- k = `2`

**Output**

- answer = `False`

**Explanation**

No matter which character we delete `s` can't become a palindrome.

### Example 2

**Input**

- s = `rzacecarx`
- k = `2`

**Output**

- answer = `True`

**Explanation**

If we remove the second and last character of `s` then we'd get `"racecar"` which is a palindrome.

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Create-Palindrome-After-Deleting-at-Most-K-Characters.cpp"></script>
