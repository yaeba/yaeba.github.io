---
title: "Line of People"
tags: ["math"]
---

You are given integers `n`, `a` and `b`. You are standing in a line of `n` people. You don't know which position you're in, but you know there are at least `a` people in front of you and at most `b` people behind you.

Return the number of possible positions you could be in.

[https://binarysearch.com/problems/Line-of-People](https://binarysearch.com/problems/Line-of-People){:target="\_blank"}

## Examples

### Example 1

**Input**

- n = `10`
- a = `3`
- b = `4`

**Output**

- answer = `5`

**Explanation**

There's `10` people and at least `3` are in front and at most `4` are behind.

This means you can be in indexes `[0, 1, 2, 3, 4]`. For example, at index `0`, `9` people are in front, `0` are behind.

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Line-of-People.cpp"></script>
