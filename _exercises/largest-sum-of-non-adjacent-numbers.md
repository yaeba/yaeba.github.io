---
title: "Largest Sum of Non-Adjacent Numbers"
tags: ["dynamic programming"]
---

Given a list of integers `nums`, write a function that returns the largest sum of non-adjacent numbers. Numbers can be `0` or negative.

**Constraints**

- `n ≤ 100,000` where `n` is the length of `nums`.

[https://binarysearch.com/problems/Largest-Sum-of-Non-Adjacent-Numbers](https://binarysearch.com/problems/Largest-Sum-of-Non-Adjacent-Numbers){:target="\_blank"}

## Examples

### Example 1

**Input**

- nums = `[2, 4, 6, 2, 5]`

**Output**

- answer = `13`

**Explanation**

We can take 2, 6, and 5 to get 13.

### Example 2

**Input**

- nums = `[5, 1, 1, 5]`

**Output**

- answer = `10`

**Explanation**

We can take 5 + 5 since they are not adjacent.

### Example 3

**Input**

- nums = `[-10, -22, -18, -3, -100]`

**Output**

- answer = `0`

**Explanation**

We don't pick any negative numbers.

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Largest-Sum-of-Non-Adjacent-Numbers.cpp"></script>
