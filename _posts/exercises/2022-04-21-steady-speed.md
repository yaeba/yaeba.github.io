---
title: "Steady Speed"
tags: ["array"]
---

You are given a list of integers `positions` representing the position of a car at equally spaced intervals of time. Return the length of the longest sublist where the car was traveling at a constant speed.

**Constraints**

- `n ≤ 100,000` where `n` is length of `positions`.

[https://binarysearch.com/problems/Steady-Speed](https://binarysearch.com/problems/Steady-Speed){:target="\_blank"}

## Examples

### Example 1

**Input**

- positions = `[0, 3, 6, 3, 0]`

**Output**

- answer = `5`

**Explanation**

The car is always traveling at `3` units of distance per time

### Example 2

**Input**

- positions = `[0, 3, 6, 5, 4, 3, 1, 7, 10, 13]`

**Output**

- answer = `4`

**Explanation**

The longest period the car was traveling at a constant speed was in the sublist `[6, 5, 4, 3]`

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Steady-Speed.py"></script>
