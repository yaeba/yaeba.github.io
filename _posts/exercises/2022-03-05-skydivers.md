---
title: "Skydivers"
tags: ["binary search"]
---

You are given a list of integers `nums` where each value represents a group of people looking to skydive together. You are also given `k` representing the number of days the skydiving facility is open for.

Return the minimum capacity of the plane you need to be able to fulfill all requests in `k` days. Note that requests should be fulfilled in the order they were given and a plane can only have one flight per day.

**Constraints**

- `n ≤ 10,000` where `n` is the length of `nums`.

[https://binarysearch.com/problems/Skydivers](https://binarysearch.com/problems/Skydivers){:target="\_blank"}

## Examples

### Example 1

**Input**

- nums = `[13, 17, 30, 15, 17]`
- k = `3`

**Output**

- answer = `32`

**Explanation**

A `32` person airplane can group the requests by `[13, 17], [30], [15, 17]`.

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Skydivers.cpp"></script>
