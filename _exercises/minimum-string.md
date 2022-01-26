---
title: "Minimum String"
tags: ["hash table"]
---

You are given two strings `s` and `t` of equal length only consisting of lowercase letters. Assuming that you can first rearrange `s` into any order, return the minimum number of changes needed to turn `s` into `t`.

**Constraints**

- `0 ≤ n ≤ 100,000` where `n` is the length of `s` and `t`

[https://binarysearch.com/problems/Minimum-String](https://binarysearch.com/problems/Minimum-String){:target="\_blank"}

## Examples

### Example 1

**Input**

- s = `ehyoe`
- t = `hello`

**Output**

- answer = `2`

**Explanation**

We can shuffle `"ehyoe"` to be `"heyeo"` and then turn `"y"` and the 2nd `"e"` into `"l"`.

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Minimum-String.cpp"></script>
