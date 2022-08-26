---
title: "String Expansion"
tags: ["string", "recursion"]
---

You are given a string `s` consisting of lowercase alphabet characters, digits, and brackets`"("` and `")"`. `s` encodes a longer string and is represented as concatenation of `n(t)`, where `n` is the number of times `t` is repeated, and `t` is either a regular string or it's another encoded string recursively.

Return the expanded version of `s`. Note that `t` can be the empty string.

[https://binarysearch.com/problems/String-Expansion](https://binarysearch.com/problems/String-Expansion){:target="\_blank"}

## Examples

### Example 1

**Input**

- s = `2(ye)0(z)2(2(po)w)`

**Output**

- answer = `yeyepopowpopow`

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=String-Expansion.py"></script>
