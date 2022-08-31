---
title: "Minimum Window Substring"
tags: ["two pointers", "string"]
---

Given two lowercase alphabet strings `a` and `b`, return the length of a minimum substring in `a` that contains all the characters of `b`.

If no such substring exists, return `-1`.

**Constraints**

- `0 ≤ n ≤ 100,000` where `n` is the length of `a`
- `1 ≤ m ≤ 100,000` where `m` is the length of `b`

[https://binarysearch.com/problems/Minimum-Window-Substring](https://binarysearch.com/problems/Minimum-Window-Substring){:target="\_blank"}

## Examples

### Example 1

**Input**

- a = `qthequickbrownfox`
- b = `qown`

**Output**

- answer = `10`

**Explanation**

The shortest substring that contains "qown" is "quickbrown" which has length of `10`.

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Minimum-Window-Substring.py"></script>
