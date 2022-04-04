---
title: "Max Sum of Two Non-Overlapping Lists"
tags: ["prefix sum"]
---

Given a list of integers `nums` and integers `a` and `b`, return the max sum of two non-overlapping sublists in `nums` which have lengths `a` and `b`.

**Constraints**

- `n ≤ 100,000` where `n` is the length of `nums`
- `1 ≤ a, b`

[https://binarysearch.com/problems/Max-Sum-of-Two-Non-Overlapping-Lists](https://binarysearch.com/problems/Max-Sum-of-Two-Non-Overlapping-Lists){:target="\_blank"}

## Examples

### Example 1

**Input**

- nums = `[2, 1, 9, -3, 6, 5]`
- a = `3`
- b = `1`

**Output**

- answer = `18`

**Explanation**

For the sublist with length `3` we pick `[2, 1, 9]` and for the other we pick `[6]`.

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Max-Sum-of-Two-Non-Overlapping-Lists.cpp"></script>
