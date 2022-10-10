---
title: "Fractional Knapsack"
tags: ["greedy"]
---

You are given two lists of integers `weights` and `values` which have the same length and an integer `capacity`. `weights[i]` and `values[i]` represent the weight and value of the `i`th item.

Given that you can take at most `capacity` weights, and that you can take a fraction of an item's weight with proportionate value, return the maximum amount of value you can get, rounded down to the nearest integer.

**Constraints**

- `n ≤ 100,000` where `n` is the length of `weights` and `values`

[https://binarysearch.com/problems/Fractional-Knapsack](https://binarysearch.com/problems/Fractional-Knapsack){:target="\_blank"}

## Examples

### Example 1

**Input**

- weights = `[5, 6, 2]`
- values = `[100, 100, 1]`
- capacity = `8`

**Output**

- answer = `150`

**Explanation**

The best we can do is:

- Take the item with `5` weight and take the `100` value, leaving us with `3` capacity
- Take half of the item with `6` weight and take half of the `100` value.

### Example 2

**Input**

- weights = `[5, 6, 2]`
- values = `[100, 100, 1]`
- capacity = `13`

**Output**

- answer = `201`

**Explanation**

We can take all `3` items in full

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Fractional-Knapsack.py"></script>
