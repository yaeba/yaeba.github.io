---
title: "Interleaved String"
tags: ["string"]
---

Given two strings `s0` and `s1`, return the two strings interleaved, starting with `s0`. If there are leftover characters in a string they should be added to the end.

**Constraints**

- `n ≤ 100,000` where `n` is the length of `s0`
- `m ≤ 100,000` where `n` is the length of `s1`

[https://binarysearch.com/problems/Interleaved-String](https://binarysearch.com/problems/Interleaved-String){:target="\_blank"}

## Examples

### Example 1

**Input**

- s0 = `abc`
- s1 = `xyz`

**Output**

- answer = `axbycz`

**Explanation**

### Example 2

**Input**

- s0 = `abc`
- s1 = `x`

**Output**

- answer = `axbc`

**Explanation**

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Interleaved-String.cpp"></script>
