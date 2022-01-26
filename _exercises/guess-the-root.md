---
title: "Guess the Root"
tags: ["binary search", "math"]
---

Given a non-negative integer `n`, find a number `r` such that `r * r = n` and round down to the nearest integer.

Can you implement this without using the built-in square root?

**Constraints**

- `0 ≤ n < 2 ** 31`

[https://binarysearch.com/problems/Guess-the-Root](https://binarysearch.com/problems/Guess-the-Root){:target="\_blank"}

## Examples

### Example 1

**Input**

- n = `9`

**Output**

- answer = `3`

**Explanation**

`3` is the square root of `9`.

### Example 2

**Input**

- n = `26`

**Output**

- answer = `5`

**Explanation**

~`5.09901951359` is the square root of `26` and rounding down gives us `5`.

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Guess-the-Root.cpp"></script>
