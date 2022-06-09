---
title: "Eat Bananas in K Hours"
tags: ["array", "binary search"]
---

You are given a list of integers `piles` and an integer `k`. `piles[i]` represents the number of bananas on pile `i`. On each hour, you can choose any pile and eat `r` number of bananas in that pile. If you pick a pile with fewer than `r` bananas, it still takes an hour to eat the pile.

Return the minimum `r` required such that you can eat all the bananas in less than or equal to `k` hours.

**Constraints**

- `n ≤ 100,000` where `n` is the length of `piles`
- `n ≤ k`

[https://binarysearch.com/problems/Eat-Bananas-in-K-Hours](https://binarysearch.com/problems/Eat-Bananas-in-K-Hours){:target="\_blank"}

## Examples

### Example 1

**Input**

- piles = `[6, 4, 3]`
- k = `5`

**Output**

- answer = `3`

**Explanation**

At `r = 3` bananas per hour, we can eat the first pile in `2` hours, eat the second in `2` hours, and eat the last pile in `1` hour.

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Eat-Bananas-in-K-Hours.py"></script>
