---
title: "Sort List by Reversing Once"
tags: ["greedy"]
---

You are given a list of integers `nums`. Given that you can first reverse one sublist in `nums`, return whether you can make the resulting list be arranged in ascending order.

**Constraints**

- `0 ≤ n ≤ 100,000` where `n` is the length of `nums`

[https://binarysearch.com/problems/Sort-List-by-Reversing-Once](https://binarysearch.com/problems/Sort-List-by-Reversing-Once){:target="\_blank"}

## Examples

### Example 1

**Input**

- nums = `[1, 3, 3, 7, 6, 9]`

**Output**

- answer = `True`

**Explanation**

If we reverse the sublist `[7, 6]`, then we can sort the list in ascending order: `[1, 3, 3, 6, 7, 9]`.

### Example 2

**Input**

- nums = `[1, 3, 9, 8, 2]`

**Output**

- answer = `False`

**Explanation**

There's no way to reverse any sublist to sort `nums` in ascending order.

### Example 3

**Input**

- nums = `[1, 2, 3, 4]`

**Output**

- answer = `True`

**Explanation**

This list is already sorted in ascending order so we can reverse any sublist of length `1`. For example, reverse `[2]` to get the same `[1, 2, 3, 4]`.

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Sort-List-by-Reversing-Once.cpp"></script>
