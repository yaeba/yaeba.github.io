---
title: "Dropped Sensor Metric"
---

You are given two lists of integers `a` and `b` representing sensor metrics. Each list contains unique integers and `a ≠ b`. One of the lists contains accurate sensor metrics but the other one is faulty. In the faulty list one number that wasn't the last number was dropped and a fake value was appended to the end of the list. Return the number that was dropped.

**Constraints**

- `2 ≤ n ≤ 100,000` where `n` is the length of `a` and `b`

[https://binarysearch.com/problems/Dropped-Sensor-Metric](https://binarysearch.com/problems/Dropped-Sensor-Metric){:target="\_blank"}

## Examples

### Example 1

**Input**

- a = `[1, 2, 3]`
- b = `[2, 3, 5]`

**Output**

- answer = `1`

**Explanation**

The accurate metrics come from `a = [1, 2, 3]`.

### Example 2

**Input**

- a = `[5, 4, 2, 1, 6]`
- b = `[5, 4, 3, 2, 1]`

**Output**

- answer = `3`

**Explanation**

The accurate metrics come from `b = [5, 4, 3, 2, 1]`.

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Dropped-Sensor-Metric.cpp"></script>
