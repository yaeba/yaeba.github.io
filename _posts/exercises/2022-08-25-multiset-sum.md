---
title: "Multiset Sum"
---

Given a list of unique positive integers `nums` and a positive integer `k`, return the number of unique combinations that sum up to `k`. You may reuse numbers when creating combinations.

**Constraints**

- `n ≤ 25` where `n` is the length of `nums`
- `1 ≤ nums[i] ≤ 250` for all `0 ≤ i < n`
- `1 ≤ k ≤ 500`

[https://binarysearch.com/problems/Multiset-Sum](https://binarysearch.com/problems/Multiset-Sum){:target="\_blank"}

## Examples

### Example 1

**Input**

- nums = `[1, 2, 3]`
- k = `2`

**Output**

- answer = `2`

**Explanation**

We can make `2` with `[1, 1]` and `[2]`.

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Multiset-Sum.cpp"></script>
