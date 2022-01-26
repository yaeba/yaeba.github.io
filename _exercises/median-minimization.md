---
title: "Median Minimization"
tags: ["math", "array"]
---

Given a list of integers `nums`, split it into two lists of equal size where the absolute difference between each list's median is as small as possible and return this difference.

Note: `length of nums / 2` is guaranteed to be odd.

**Constraints**

- `n ≤ 100,000` where `n` is the length of `nums`

[https://binarysearch.com/problems/Median-Minimization](https://binarysearch.com/problems/Median-Minimization){:target="\_blank"}

## Examples

### Example 1

**Input**

- nums = `[1, 9, 7, 4, 3, 6]`

**Output**

- answer = `2`

**Explanation**

We can partition the list into `[1, 4, 9]` and `[3, 6, 7]`. Their medians are `4` and `6` and `abs(4 - 6) = 2`

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Median-Minimization.cpp"></script>
