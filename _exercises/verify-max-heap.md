---
title: "Verify Max Heap"
---

Given a list of integers `nums`, return whether it represents a max heap. That is, for every `i` we have that:

- `nums[i] ≥ nums[2*i + 1]` if `2*i + 1` is within bounds
- `nums[i] ≥ nums[2*i + 2]` if `2*i + 2` is within bounds

**Constraints**

- `0 ≤ n ≤ 100,000` where `n` is the length of `nums`

[https://binarysearch.com/problems/Verify-Max-Heap](https://binarysearch.com/problems/Verify-Max-Heap){:target="\_blank"}

## Examples

### Example 1

**Input**

- nums = `[4, 2, 3, 0, 1]`

**Output**

- answer = `True`

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Verify-Max-Heap.py"></script>
