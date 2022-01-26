---
title: "A Number and Its Triple"
tags: ["hash table"]
---

Given a list of integers `nums`, return whether there's two numbers such that one is a triple of another.

**Constraints**

- `n ≤ 100,000` where `n` is the length of `nums`.

[https://binarysearch.com/problems/A-Number-and-Its-Triple](https://binarysearch.com/problems/A-Number-and-Its-Triple){:target="\_blank"}

## Examples

### Example 1

**Input**

- nums = `[2, 3, 10, 7, 6]`

**Output**

- answer = `True`

**Explanation**

`6` is a triple of `2`

### Example 2

**Input**

- nums = `[3, 4, 5]`

**Output**

- answer = `False`

**Explanation**

There's no `9`, `12`, or `15`.

### Example 3

**Input**

- nums = `[0, 2, 0]`

**Output**

- answer = `True`

**Explanation**

`0` is a triple of `0`

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=A-Number-and-Its-Triple.cpp"></script>
