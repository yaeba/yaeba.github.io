---
title: "Social Distancing"
---

You are given a string `s` and an integer `k`. Each character in the string is either `'.'` or `'x'`, where `'.'` represents an empty space and `'x'` represents a person.

Return whether it's possible to choose a position to stand on such that the distance between you and the closest person to you is at least `k`. (The distance between each neighbouring indices is `1`).

**Constraints**

- `1 ≤ k ≤ n ≤ 100,000` where `n` is the length of `s`

[https://binarysearch.com/problems/Social-Distancing](https://binarysearch.com/problems/Social-Distancing){:target="\_blank"}

## Examples

### Example 1

**Input**

- s = `x...x`
- k = `2`

**Output**

- answer = `True`

**Explanation**

You can stand at `s[2]`.

### Example 2

**Input**

- s = `x..`
- k = `2`

**Output**

- answer = `True`

**Explanation**

You can stand at `s[2]`

### Example 3

**Input**

- s = `x..x`
- k = `2`

**Output**

- answer = `False`

**Explanation**

There's a person standing next to both of the empty spaces (distance of `1`).

### Example 4

**Input**

- s = `..x`
- k = `2`

**Output**

- answer = `True`

**Explanation**

You can stand at `s[0]`

### Example 5

**Input**

- s = `.`
- k = `1`

**Output**

- answer = `True`

**Explanation**

You can stand at `s[0]`

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Social-Distancing.py"></script>
