---
title: "Strictly Increasing or Strictly Decreasing"
tags: ["array"]
---

Given a list of integers `nums`, return whether the list is strictly increasing or strictly decreasing.

**Constraints**

- `n ≤ 100,000` where `n` is the length of `nums`

[https://binarysearch.com/problems/Strictly-Increasing-or-Strictly-Decreasing](https://binarysearch.com/problems/Strictly-Increasing-or-Strictly-Decreasing){:target="\_blank"}

## Examples

### Example 1

**Input**

- nums = `[1, 2, 3, 4, 5, 5]`

**Output**

- answer = `False`

**Explanation**

Since there's two duplicate `5` this is not strictly increasing.

### Example 2

**Input**

- nums = `[5, 4, 3, 2, 1]`

**Output**

- answer = `True`

**Explanation**

This is strictly decreasing.

### Example 3

**Input**

- nums = `[1, 2, 3, 4, 5]`

**Output**

- answer = `True`

**Explanation**

This is strictly increasing.

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Strictly-Increasing-or-Strictly-Decreasing.cpp"></script>
