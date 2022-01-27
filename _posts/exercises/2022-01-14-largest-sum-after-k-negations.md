---
title: "Largest Sum After K Negations"
tags: ["array"]
---

You are given a list of integers `nums` and an integer `k`. Consider an operation where you pick an element in `nums` and negate it. Given that you must make exactly `k` operations, return the maximum resulting sum that can be obtained.

**Constraints**

- `n ≤ 100,000` where `n` is the length of `nums`
- `k < 2 ** 31`

[https://binarysearch.com/problems/Largest-Sum-After-K-Negations](https://binarysearch.com/problems/Largest-Sum-After-K-Negations){:target="\_blank"}

## Examples

### Example 1

**Input**

- nums = `[1, 0, -5, -3]`
- k = `4`

**Output**

- answer = `9`

**Explanation**

We can negate `-5` and `-3` once each and `0` twice to get `[1, 0, 5, 3]` and its sum is `9`.

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Largest-Sum-After-K-Negations.cpp"></script>
