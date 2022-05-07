---
title: "Lexicographically Smallest String of Distance K"
tags: ["greedy", "string"]
---

A distance of a lowercase alphabet character is defined to be its index (1-indexed) in the alphabet. For example `"a"` is `1`, `"b"` is `2` and `"z"` is `26`. The distance of a lowercase alphabet string is the sum of its character distances.

Given two integers `n` and `k`, return the lexicographically smallest lowercase alphabet string of length `k` whose distance is equal to `n`.

**Constraints**

- `n ≤ 100,000`

[https://binarysearch.com/problems/Lexicographically-Smallest-String-of-Distance-K](https://binarysearch.com/problems/Lexicographically-Smallest-String-of-Distance-K){:target="\_blank"}

## Examples

### Example 1

**Input**

- n = `30`
- k = `4`

**Output**

- answer = `aabz`

**Explanation**

This is the lexicographically smallest string of length `4` whose distance is `1 + 1 + 2 + 26 = 30`.

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Lexicographically-Smallest-String-of-Distance-K.py"></script>
