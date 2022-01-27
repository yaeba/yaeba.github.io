---
title: "Index Into an Infinite String"
tags: ["string"]
---

You are given an alphabet (can be lower or uppercase) string `s` and two integers `i` and `j` where `i < j`. Let's say `p` is an infinite string of `s` repeating forever. Return the substring of `p` from indexes `[i, j)`.

**Constraints**

- `1 ≤ n ≤ 100,000` where `n` is the length of `s
- `0 ≤ i < j < 2 ** 31`

[https://binarysearch.com/problems/Index-Into-an-Infinite-String](https://binarysearch.com/problems/Index-Into-an-Infinite-String){:target="\_blank"}

## Examples

### Example 1

**Input**

- s = `tiger`
- i = `6`
- j = `8`

**Output**

- answer = `ig`

**Explanation**

### Example 2

**Input**

- s = `hi`
- i = `2`
- j = `6`

**Output**

- answer = `hihi`

**Explanation**

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Index-Into-an-Infinite-String.cpp"></script>
