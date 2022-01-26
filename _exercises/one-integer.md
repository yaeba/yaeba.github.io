---
title: "One Integer"
tags: ["heap"]
---

You are given a list of integers `nums`. You can reduce the length of `nums` by taking any two integers, removing them, and appending their sum to the end. The cost of doing this is the sum of the two integers you removed.

Return the minimum total cost of reducing `nums` to one integer.

**Constraints**

- `n ≤ 100,000` where `n` is length of `nums`.

[https://binarysearch.com/problems/One-Integer](https://binarysearch.com/problems/One-Integer){:target="\_blank"}

## Examples

### Example 1

**Input**

- nums = `[1, 2, 3, 4, 5]`

**Output**

- answer = `33`

**Explanation**

- We take `1` and `2` out to get `[3, 4, 5, 3]`
- We take `3` and `3` out to get `[4, 5, 6]`
- We take `4` and `5` out to get `[6, 9]`
- We take `6` and `9` out to get `[15]`

- The sum is `33 = 1 + 2 + 3 + 3 + 4 + 5 + 6 + 9`

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=One-Integer.py"></script>
