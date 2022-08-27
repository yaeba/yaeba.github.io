---
title: "Dividing Station"
tags: ["array"]
---

Given a list of distinct positive integers `nums`, find the largest subset such that every pair of elements in the subset (`i`, `j`) satisfies either `i % j = 0` or `j % i = 0`. Return the size of this subset.

**Constraints**

- `n ≤ 1,000` where `n` is the length of `nums`

[https://binarysearch.com/problems/Dividing-Station](https://binarysearch.com/problems/Dividing-Station){:target="\_blank"}

## Examples

### Example 1

**Input**

- nums = `[3, 5, 10, 20, 21]`

**Output**

- answer = `3`

**Explanation**

The largest satisfying subset is `[5, 10, 20]`.

### Example 2

**Input**

- nums = `[1, 3, 6, 24]`

**Output**

- answer = `4`

**Explanation**

The largest satisfying subset is `[1, 3, 6, 24]`.

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Dividing-Station.py"></script>
