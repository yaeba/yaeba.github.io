---
title: "Repeated K-Length Substrings"
---

Given a string `s` and an integer `k`, return the number of k-length substrings that occur more than once in `s`.

**Constraints**

- `n ≤ 100,000` where `n` is the length of `s`.
- `k ≤ 10`

[https://binarysearch.com/problems/Repeated-K-Length-Substrings](https://binarysearch.com/problems/Repeated-K-Length-Substrings){:target="\_blank"}

## Examples

### Example 1

**Input**

- s = `abcdabc`
- k = `3`

**Output**

- answer = `1`

**Explanation**

`"abc"` occurs twice in the string

### Example 2

**Input**

- s = `aaabbb`
- k = `2`

**Output**

- answer = `2`

**Explanation**

Both `"aa"` and `"bb"` occurs twice.

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Repeated-K-Length-Substrings.py"></script>
