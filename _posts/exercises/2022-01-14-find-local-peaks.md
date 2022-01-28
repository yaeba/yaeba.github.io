---
title: "Find Local Peaks"
tags: ["greedy"]
---

You are given a list of integers `nums`. Return the index of every peak in the list, sorted in ascending order. An index `i` is called a peak if:

- `nums[i] > nums[i + 1]` if `i = 0`
- `nums[i] > nums[i - 1]` if `i = n - 1`
- `nums[i - 1] < nums[i] > nums[i + 1]` otherwise

However, a list of length `1` is not considered a peak.

**Constraints**

- `0 ≤ n ≤ 100,000` where `n` is the length of `nums`

[https://binarysearch.com/problems/Find-Local-Peaks](https://binarysearch.com/problems/Find-Local-Peaks){:target="\_blank"}

## Examples

### Example 1

**Input**

- nums = `[3, 4]`

**Output**

- answer = `[1]`

### Example 2

**Input**

- nums = `[1, 2, 3, 2, 4]`

**Output**

- answer = `[2, 4]`

**Explanation**

The values at index `2` and `4` are considered peaks since they are larger than their neighbors.

### Example 3

**Input**

- nums = `[5]`

**Output**

- answer = `[]`

### Example 4

**Input**

- nums = `[1, 1, 1, 1]`

**Output**

- answer = `[]`

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Find-Local-Peaks.cpp"></script>
