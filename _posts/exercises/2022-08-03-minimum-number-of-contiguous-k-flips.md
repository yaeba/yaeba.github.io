---
title: "Minimum Number of Contiguous K-Flips"
---

You are given a list of integers `nums` containing `1`s and `0`s and an integer `k`. Consider an operation where we flip a sublist of length `k` such that all `1`s become `0`s and all `0`s become `1`s.

Return the minimum number of operations required to turn `nums` into all `0`s. If it's not possible return `-1`.

**Constraints**

- `k ≤ n ≤ 100,000` where `n` is the length of `nums`.

[https://binarysearch.com/problems/Minimum-Number-of-Contiguous-K-Flips](https://binarysearch.com/problems/Minimum-Number-of-Contiguous-K-Flips){:target="\_blank"}

## Examples

### Example 1

**Input**

- nums = `[1, 1, 1]`
- k = `2`

**Output**

- answer = `-1`

**Explanation**

There's no way to flip the numbers such that they all become `0`s.

### Example 2

**Input**

- nums = `[1, 1, 0, 1, 1]`
- k = `2`

**Output**

- answer = `2`

**Explanation**

We can flip the first two numbers to zero and then flip the last two numbers to zero.

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Minimum-Number-of-Contiguous-K-Flips.py"></script>
