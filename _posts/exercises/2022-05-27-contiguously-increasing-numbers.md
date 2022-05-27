---
title: "Contiguously Increasing Numbers"
---

Given two integers `start` and `end`, return a sorted list of integers such that every number `e` is between `start ≤ e ≤ end` and the digits of `e` are contiguously increasing. For example, `2345` is contiguously increasing while `135` and `321` are not.

**Constraints**

- `0 ≤ start ≤ end < 2 ** 31`

[https://binarysearch.com/problems/Contiguously-Increasing-Numbers](https://binarysearch.com/problems/Contiguously-Increasing-Numbers){:target="\_blank"}

## Examples

### Example 1

**Input**

- start = `0`
- end = `100`

**Output**

- answer = `[1, 2, 3, 4, 5, 6, 7, 8, 9, 12, 23, 34, 45, 56, 67, 78, 89]`

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Contiguously-Increasing-Numbers.py"></script>
