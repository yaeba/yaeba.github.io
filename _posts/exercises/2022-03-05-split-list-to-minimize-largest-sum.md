---
title: "Split List to Minimize Largest Sum"
tags: ["binary search"]
---

Given a list of non-negative integers `nums` and an integer `k`, you can split the list into `k` non-empty sublists.

Return the minimum largest sum of the `k` sublists.

**Constraints**

- `k ≤ n ≤ 100,000` where `n` is the length of `nums`

[https://binarysearch.com/problems/Split-List-to-Minimize-Largest-Sum](https://binarysearch.com/problems/Split-List-to-Minimize-Largest-Sum){:target="\_blank"}

## Examples

### Example 1

**Input**

- nums = `[1, 3, 2, 4, 9]`
- k = `2`

**Output**

- answer = `10`

**Explanation**

We can split the list into these `2` sublists: `[1, 3, 2, 4]` and `[9]`.

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Split-List-to-Minimize-Largest-Sum.cpp"></script>
