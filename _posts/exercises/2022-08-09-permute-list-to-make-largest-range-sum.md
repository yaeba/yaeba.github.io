---
title: "Permute List to Make Largest Range Sum"
tags: ["array"]
---

You are given a list of integers `nums` and a two-dimensional list of integers `ranges`. Each element in `ranges` contains `[i, j]`, meaning to sum the numbers in `nums` between `i` to `j` inclusive.

Given that you can first permute `nums` in any order, return the maximum possible total of all range sums. Return the result mod `10 ** 9 + 7`.

**Constraints**

- `0 ≤ n ≤ 100,000` where `n` is the length of `nums`
- `0 ≤ m ≤ 100,000` where `m` is the length of `ranges`

[https://binarysearch.com/problems/Permute-List-to-Make-Largest-Range-Sum](https://binarysearch.com/problems/Permute-List-to-Make-Largest-Range-Sum){:target="\_blank"}

## Examples

### Example 1

**Input**

- nums = `[1, 2, 3, 4, 5, 6]`
- ranges =

```
[[0,1],
 [1,3]]
```

**Output**

- answer = `24`

**Explanation**

If we permute the list to `[5,6,4,3,2,1]` then `[5, 6]` sums to `11` and `[6, 4, 3]` sums to `13`.

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Permute-List-to-Make-Largest-Range-Sum.py"></script>
