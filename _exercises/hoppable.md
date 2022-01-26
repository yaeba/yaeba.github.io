---
title: "Hoppable"
tags: ["array", "dynamic programming"]
---

Given an integer list `nums` where each number represents the maximum number of hops you can make, determine whether you can reach to the last index starting at index `0`.

**Constraints**

- `n ≤ 100,000` where `n` is the length of `nums`.

[https://binarysearch.com/problems/Hoppable](https://binarysearch.com/problems/Hoppable){:target="\_blank"}

## Examples

### Example 1

**Input**

- nums = `[1, 1, 0, 1]`

**Output**

- answer = `False`

**Explanation**

We can't go past index `2` of the array.

### Example 2

**Input**

- nums = `[2, 4, 0, 1, 0]`

**Output**

- answer = `True`

**Explanation**

We can jump from index `0` to `1`, and then jump to the end.

### Example 3

**Input**

- nums = `[1, 0, 0, 0]`

**Output**

- answer = `False`

**Explanation**

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Hoppable.cpp"></script>
