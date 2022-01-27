---
title: "Run-Length Encoding"
tags: ["string"]
---

Given a string `s`, return its run-length encoding. You can assume the string to be encoded have no digits and consists solely of alphabetic characters.

**Constraints**

- `n ≤ 100,000` where `n` is the length of `s`

[https://binarysearch.com/problems/Run-Length-Encoding](https://binarysearch.com/problems/Run-Length-Encoding){:target="\_blank"}

## Examples

### Example 1

**Input**

- s = `abcde`

**Output**

- answer = `1a1b1c1d1e`

### Example 2

**Input**

- s = `aabba`

**Output**

- answer = `2a2b1a`

### Example 3

**Input**

- s = `aaaabbbccdaa`

**Output**

- answer = `4a3b2c1d2a`

### Example 4

**Input**

- s = `aaaaaaaaaa`

**Output**

- answer = `10a`

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Run-Length-Encoding.cpp"></script>
