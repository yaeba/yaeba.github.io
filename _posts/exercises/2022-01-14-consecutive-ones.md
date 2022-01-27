---
title: "Consecutive Ones"
tags: ["greedy", "array"]
---

You are given a list of integers `nums` which contains at least one `1`. Return whether all the `1`s appear consecutively.

**Constraints**

- `1 ≤ n ≤ 100,000` where `n` is the length of `nums`

[https://binarysearch.com/problems/Consecutive-Ones](https://binarysearch.com/problems/Consecutive-Ones){:target="\_blank"}

## Examples

### Example 1

**Input**

- nums = `[0, 1, 1, 1, 2, 3]`

**Output**

- answer = `True`

**Explanation**

All the `1`s appear consecutively here in the middle.

### Example 2

**Input**

- nums = `[1, 1, 0, 1, 1]`

**Output**

- answer = `False`

**Explanation**

There's two groups of consecutive `1`s.

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Consecutive-Ones.cpp"></script>
