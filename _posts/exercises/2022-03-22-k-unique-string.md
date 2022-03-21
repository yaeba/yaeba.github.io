---
title: "K Unique String"
tags: ["heap", "hash table"]
---

Given a string `s` of lowercase alphabet characters, and an integer `k`, return the minimum number of changes needed in the string (one change involves changing a single character to any other character) so that the resulting string has at most `k` distinct characters.

**Constraints**

- `n ≤ 10,000` where `n` is the length of `s`
- `1 ≤ k ≤ 26`

[https://binarysearch.com/problems/K-Unique-String](https://binarysearch.com/problems/K-Unique-String){:target="\_blank"}

## Examples

### Example 1

**Input**

- s = `daabbccaa`
- k = `3`

**Output**

- answer = `1`

**Explanation**

We can remove the "d" to get 3 distinct characters (a, b, and c).

### Example 2

**Input**

- s = `daabbccaad`
- k = `3`

**Output**

- answer = `2`

**Explanation**

We must remove either 2 "b"s, 2 "c"s, or 2 "d"s.

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=K-Unique-String.py"></script>
