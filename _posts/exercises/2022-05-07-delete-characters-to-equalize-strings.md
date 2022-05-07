---
title: "Delete Characters to Equalize Strings"
tags: ["dynamic programming", "string"]
---

Given two lowercase alphabet strings `a` and `b`, consider an operation where we delete any character in either string. Return the minimum number of operations required such that both strings are equal.

**Constraints**

- `0 ≤ n ≤ 1,000` where `n` is the length of `a`
- `0 ≤ m ≤ 1,000` where `m` is the length of `b`

[https://binarysearch.com/problems/Delete-Characters-to-Equalize-Strings](https://binarysearch.com/problems/Delete-Characters-to-Equalize-Strings){:target="\_blank"}

## Examples

### Example 1

**Input**

- a = `zyyx`
- b = `yfyx`

**Output**

- answer = `2`

**Explanation**

We delete the `"z"` in `a` and delete `"f"` in `b`

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Delete-Characters-to-Equalize-Strings.cpp"></script>
