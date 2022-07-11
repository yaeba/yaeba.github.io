---
title: "Next Integer Permutation"
tags: ["array"]
---

Given an integer `n`, return the next bigger permutation of its digits.

If `n` is already in its biggest permutation, rotate to the smallest permutation.

**Constraints**

- `n < 2 ** 31`

[https://binarysearch.com/problems/Next-Integer-Permutation](https://binarysearch.com/problems/Next-Integer-Permutation){:target="\_blank"}

## Examples

### Example 1

**Input**

- n = `321`

**Output**

- answer = `123`

**Explanation**

321 is already the biggest permutation so it rotates to the smallest.

### Example 2

**Input**

- n = `527`

**Output**

- answer = `572`

### Example 3

**Input**

- n = `20`

**Output**

- answer = `2`

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Next-Integer-Permutation.cpp"></script>
