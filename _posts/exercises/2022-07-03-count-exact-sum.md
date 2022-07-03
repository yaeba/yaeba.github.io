---
title: "Count Exact Sum"
tags: ["dynamic programming"]
---

Given a list of positive integers `nums` and an integer `k`, return the number of subsets in the list that sum up to `k`.

Mod the result by `10 ** 9 + 7`.

**Constraints**

- `n ≤ 300` where `n` is the length of `nums`.
- `k ≤ 300`.

[https://binarysearch.com/problems/Count-Exact-Sum](https://binarysearch.com/problems/Count-Exact-Sum){:target="\_blank"}

## Examples

### Example 1

**Input**

- nums = `[1, 2, 3, 4, 5]`
- k = `5`

**Output**

- answer = `3`

**Explanation**

We can choose the subsets [1,4],[2,3] and [5].

### Example 2

**Input**

- nums = `[1, 2, 3, 4, 5]`
- k = `10`

**Output**

- answer = `3`

**Explanation**

We can choose the subsets [1,4,5],[2,3,5] and [1,2,3,4].

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Count-Exact-Sum.py"></script>
