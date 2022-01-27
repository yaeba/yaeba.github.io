---
title: "Missing Numbers From 1 to N"
---

You are given a list of integers `nums` of length `n` where all numbers in the list are from the interval $$[1, n]$` and some elements appear twice while others only once. Return all the numbers from `$[1, n]$$ that are not in the list, sorted in ascending order.

Can you do it in $$\mathcal{O}(n)$` time, modify `nums` in-place and use `$\mathcal{O}(1)$$ additional space?

**Constraints**

- `n ≤ 100,000` where `n` is the length of `nums`

[https://binarysearch.com/problems/Missing-Numbers-From-1-to-N](https://binarysearch.com/problems/Missing-Numbers-From-1-to-N){:target="\_blank"}

## Examples

### Example 1

**Input**

- nums = `[3, 3, 1, 1, 5, 5]`

**Output**

- answer = `[2, 4, 6]`

**Explanation**

The list contains `6` elements so `n = 6`. So the numbers `[2, 4, 6]` are missing from `[1, 6]`

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Missing-Numbers-From-1-to-N.cpp"></script>
