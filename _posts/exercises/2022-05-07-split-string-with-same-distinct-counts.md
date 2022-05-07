---
title: "Split String with Same Distinct Counts"
tags: ["string"]
---

You are given a lowercase alphabet string `s`. Return the number of ways to split the string into two strings such that the number of distinct characters in each string is the same.

**Constraints**

- `1 ≤ n ≤ 100,000` where `n` is the length of `s`

[https://binarysearch.com/problems/Split-String-with-Same-Distinct-Counts](https://binarysearch.com/problems/Split-String-with-Same-Distinct-Counts){:target="\_blank"}

## Examples

### Example 1

**Input**

- s = `abaab`

**Output**

- answer = `2`

**Explanation**

We can split it by `"ab" + "aab"` and `"aba" + "ab"`

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Split-String-with-Same-Distinct-Counts.py"></script>
