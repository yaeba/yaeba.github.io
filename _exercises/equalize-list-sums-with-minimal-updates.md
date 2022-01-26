---
title: "Equalize List Sums with Minimal Updates"
tags: ["two pointers", "greedy"]
---

You are given two lists of integers `a` and `b` where every element in both lists is between `1` to `6`. Consider an operation where you pick a number in either `a` or `b` and update its value to a number between `1` to `6`.

Return the minimum number of operations required such that the sum of `a` and `b` are equal. If it's not possible, return `-1`.

**Constraints**

- `n ≤ 100,000` where `n` is the length of `a`
- `m ≤ 100,000` where `m` is the length of `b`

[https://binarysearch.com/problems/Equalize-List-Sums-with-Minimal-Updates](https://binarysearch.com/problems/Equalize-List-Sums-with-Minimal-Updates){:target="\_blank"}

## Examples

### Example 1

**Input**

- a = `[1, 5]`
- b = `[6, 5, 5]`

**Output**

- answer = `2`

**Explanation**

If we change the `1` to `6` in `a` and the `6` to `1` in `b`, then both of their sums would be `11`.

### Example 2

**Input**

- a = `[6]`
- b = `[1, 1, 1, 1, 1, 1, 1]`

**Output**

- answer = `-1`

**Explanation**

There's no way to make `a` and `b`'s sums equal.

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Equalize-List-Sums-with-Minimal-Updates.cpp"></script>
