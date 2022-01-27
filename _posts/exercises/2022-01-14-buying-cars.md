---
title: "Buying Cars"
tags: ["greedy", "array"]
---

Given a list of integers `prices` representing prices of cars for sale, and a budget `k`, return the maximum number of cars you can buy.

**Constraints**

- `n ≤ 200,000` where `n` is the length of `prices`

[https://binarysearch.com/problems/Buying-Cars](https://binarysearch.com/problems/Buying-Cars){:target="\_blank"}

## Examples

### Example 1

**Input**

- prices = `[90, 30, 20, 40, 90]`
- k = `95`

**Output**

- answer = `3`

**Explanation**

We can buy the cars with prices 30, 20, and 40.

### Example 2

**Input**

- prices = `[60, 90, 55, 75]`
- k = `50`

**Output**

- answer = `0`

**Explanation**

We cannot afford any of these cars.

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Buying-Cars.cpp"></script>
