---
title: "Hamming Distance"
tags: ["bit manipulation"]
---

Given two integers `x`, and `y` return the number of positions where their values differ in their binary representations as a 32-bit integer.

**Constraints**

- `0 ≤ x, y < 2 ** 31 `

[https://binarysearch.com/problems/Hamming-Distance](https://binarysearch.com/problems/Hamming-Distance){:target="\_blank"}

## Examples

### Example 1

**Input**

- x = `9`
- y = `5`

**Output**

- answer = `2`

**Explanation**

`9` in binary is `1001` and `5` in binary is `0101`, so indices 2 and 3 are different.

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Hamming-Distance.cpp"></script>
