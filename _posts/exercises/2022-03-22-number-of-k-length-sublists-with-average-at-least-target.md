---
title: "Number of K-Length Sublists with Average at Least Target"
tags: ["prefix sum"]
---

Given a list of integers `nums`, and integers `k` and `target`, return the number of sublists whose length is `k` and its average value `≥ target`.

**Constraints**

- `n ≤ 100,000` where `n` is the length of `nums`

[https://binarysearch.com/problems/Number-of-K-Length-Sublists-with-Average-at-Least-Target](https://binarysearch.com/problems/Number-of-K-Length-Sublists-with-Average-at-Least-Target){:target="\_blank"}

## Examples

### Example 1

**Input**

- nums = `[0, 9, 4, 5, 6]`
- k = `3`
- target = `5`

**Output**

- answer = `2`

**Explanation**

Sublist `[9, 4, 5]` has average value of `6` and `[4, 5, 6]` has average of `5`

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Number-of-K-Length-Sublists-with-Average-at-Least-Target.py"></script>
