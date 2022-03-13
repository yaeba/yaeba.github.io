---
title: "Count Substrings With All 1s"
tags: ["math", "string"]
---

You are given a string `s` containing `"1"`s and `"0"`s. Return the number of substrings that contain only `"1"`s. Mod the result by `10 ** 9 + 7`.

**Constraints**

- `0 ≤ n ≤ 100,000` where `n` is the length of `s`

[https://binarysearch.com/problems/Count-Substrings-With-All-1s](https://binarysearch.com/problems/Count-Substrings-With-All-1s){:target="\_blank"}

## Examples

### Example 1

**Input**

- s = `111001`

**Output**

- answer = `7`

**Explanation**

Here are all the substrings containing only `"1"`s:

- `"1"`
- `"1"`
- `"1"`
- `"1"`
- `"11"`
- `"11"`
- `"111"`

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Count-Substrings-With-All-1s.cpp"></script>
