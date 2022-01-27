---
title: "Turtle of Wall Street"
---

You are given a list of integers `nums` representing stock prices of a company in chronological order. You can buy at most one share of stock per day, but you can hold onto multiple stocks and can sell stocks on any number of days. Return the maximum profit you can earn.

**Constraints**

- `n ≤ 100,000` where `n` is the length of `nums`

[https://binarysearch.com/problems/Turtle-of-Wall-Street](https://binarysearch.com/problems/Turtle-of-Wall-Street){:target="\_blank"}

## Examples

### Example 1

**Input**

- nums = `[1, 2, 5, 1, 3]`

**Output**

- answer = `9`

**Explanation**

We buy the stocks at `1` and `2` and then sell them at `5`. We then buy at `1` and then sell at `3`. In total we make `(5 - 1) + (5 - 2) + (3 - 1)`

### Example 2

**Input**

- nums = `[5, 2]`

**Output**

- answer = `0`

**Explanation**

There's no profit that can be made.

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Turtle-of-Wall-Street.java"></script>
