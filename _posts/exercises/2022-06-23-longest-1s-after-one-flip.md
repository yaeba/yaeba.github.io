---
title: "Longest 1s After One Flip"
tags: ["two pointers", "string"]
---

You are given a string `s` containing `1`s and `0`s. Given that you can flip at most one `"0"`, return the length of the longest contiguous substring of `1`s.

**Constraints**

- `n ≤ 100,000` where `n` is the length of `s`.

[https://binarysearch.com/problems/Longest-1s-After-One-Flip](https://binarysearch.com/problems/Longest-1s-After-One-Flip){:target="\_blank"}

## Examples

### Example 1

**Input**

- s = `10110`

**Output**

- answer = `4`

**Explanation**

If we flip the first zero then we get `"11110"`.

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Longest-1s-After-One-Flip.py"></script>
