---
title: "Find the Largest Number in a Rotated List"
tags: ["binary search", "array"]
---

You are given a list of unique integers `nums` that is sorted in ascending order and is rotated at some pivot point. Find the maximum number in the rotated list.

Can you solve it in $$\mathcal{O}(\log{}n)$$?

**Constraints**

- `n ≤ 100,000` where `n` is the length of `nums`.

[https://binarysearch.com/problems/Find-the-Largest-Number-in-a-Rotated-List](https://binarysearch.com/problems/Find-the-Largest-Number-in-a-Rotated-List){:target="\_blank"}

## Examples

### Example 1

**Input**

- arr = `[6, 7, 8, 1, 4]`

**Output**

- answer = `8`

**Explanation**

The original sorted array of `[1, 4, 6, 7, 8]` was rotated at index `2` and results in the input array `[6, 7, 8, 1, 4,]`. And the largest number is `8`.

### Example 2

**Input**

- arr = `[1, 2, 3]`

**Output**

- answer = `3`

### Example 3

**Input**

- arr = `[1]`

**Output**

- answer = `1`

### Example 4

**Input**

- arr = `[10, 1, 2, 3, 4, 7]`

**Output**

- answer = `10`

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Find-the-Largest-Number-in-a-Rotated-List.cpp"></script>
