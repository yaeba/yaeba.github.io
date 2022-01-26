---
title: "Append List to Sum Target"
---

You are given a list of integers `nums` and integers `k` and `target`. Consider an operation where we choose an integer `-k ≤ e ≤ k` and append it to `nums`.

Return the minimum number of operations required such that the sum of `nums` equals to `target`.

**Constraints**

- `n ≤ 100,000` where `n` is the length of `nums`
- `1 ≤ k < 2 ** 31`

[https://binarysearch.com/problems/Append-List-to-Sum-Target](https://binarysearch.com/problems/Append-List-to-Sum-Target){:target="\_blank"}

## Examples

### Example 1

**Input**

- nums = `[2, 1]`
- k = `3`
- target = `10`

**Output**

- answer = `3`

**Explanation**

We can append `[3, 3, 1]` to get `[2, 1, 3, 3, 1]` for a total sum of `10`.

### Example 2

**Input**

- nums = `[2, 1]`
- k = `2`
- target = `-4`

**Output**

- answer = `4`

**Explanation**

We can append `[-2, -2, -2, -1]` to get `[2, 1, -2, -2, -2, -1]` for a total sum of `-4`.

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Append-List-to-Sum-Target.cpp"></script>
