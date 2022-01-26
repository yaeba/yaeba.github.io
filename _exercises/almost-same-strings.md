---
title: "Almost Same Strings"
---

You are given a list of lowercase alphabet strings `words` where each string is of the same length. Return whether there's two strings that differ only in one index.

**Constraints**

- `1 ≤ n ≤ 100,000` where `n` is the total number of characters in `words`

[https://binarysearch.com/problems/Almost-Same-Strings](https://binarysearch.com/problems/Almost-Same-Strings){:target="\_blank"}

## Examples

### Example 1

**Input**

- words = `['abcd', 'aaaa', 'abcf']`

**Output**

- answer = `True`

**Explanation**

We see that `"abcd"` and `"abcf"` only differ in the last index.

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Almost-Same-Strings.py"></script>
