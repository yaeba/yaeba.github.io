---
title: "Flip to Zeros"
---

You are given an integer list `nums` containing `0`s and `1`s. Consider an operation where we pick an index `i` in `nums` and flip `i` as well as all numbers to the right of `i`. Return the minimum number of operations required to make `nums` contain all `0`s.

**Constraints**

- `n ≤ 100,000` where `n` is the length of `nums`.

[https://binarysearch.com/problems/Flip-to-Zeros](https://binarysearch.com/problems/Flip-to-Zeros){:target="\_blank"}

## Examples

### Example 1

**Input**

- nums = `[1, 1, 0]`

**Output**

- answer = `2`

**Explanation**

We can flip at index `0` to get `[0, 0, 1]` and then flip at index `2` to get `[0, 0, 0]`

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Flip-to-Zeros.cpp"></script>
