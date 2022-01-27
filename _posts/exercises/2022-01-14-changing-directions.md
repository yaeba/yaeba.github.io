---
title: "Changing Directions"
---

Given a list of integers `nums`, return the number of times that the list changes from positive-to-negative or negative-to-positive slope.

**Constraints**

- `n ≤ 100,000` where `n` is the length of `nums`

[https://binarysearch.com/problems/Changing-Directions](https://binarysearch.com/problems/Changing-Directions){:target="\_blank"}

## Examples

### Example 1

**Input**

- nums = `[1, 3, 9, 7, 5, 10, 12]`

**Output**

- answer = `2`

**Explanation**

Change of direction happens at `9` (positive-to-negative slope), and then at `5` (negative-to-positive slope).

### Example 2

**Input**

- nums = `[1, 2, 3, 3, 2, 1]`

**Output**

- answer = `0`

**Explanation**

The slope is `0` between `[3, 3]`. So there are no positive-to-negative or negative-to-positive changes in slope since 0 is neither positive nor negative.

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Changing-Directions.cpp"></script>
