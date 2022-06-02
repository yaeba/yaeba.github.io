---
title: "Circular Greater Element to the Right"
---

You are given a list of integers `nums`. Return a new list of the same length where the value at index `i` is set to the next element greater than `nums[i]` to its right, circling back to the front of the list if necessary. If there's no number that's greater, then it should be set to `-1`.

**Constraints**

- `n ≤ 100,000` where `n` is the length of `nums`

[https://binarysearch.com/problems/Circular-Greater-Element-to-the-Right](https://binarysearch.com/problems/Circular-Greater-Element-to-the-Right){:target="\_blank"}

## Examples

### Example 1

**Input**

- nums = `[3, 4, 0, 2]`

**Output**

- answer = `[4, -1, 2, 3]`

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Circular-Greater-Element-to-the-Right.py"></script>
