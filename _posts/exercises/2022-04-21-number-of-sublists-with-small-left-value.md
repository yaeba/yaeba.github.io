---
title: "Number of Sublists With Small Left Value"
---

Given a list of integers `nums`, return the number of sublists where the first element is not bigger than other numbers in the sublist.

**Constraints**

- `0 ≤ n ≤ 100,000` where `n` is the length of `nums`

[https://binarysearch.com/problems/Number-of-Sublists-With-Small-Left-Value](https://binarysearch.com/problems/Number-of-Sublists-With-Small-Left-Value){:target="\_blank"}

## Examples

### Example 1

**Input**

- nums = `[1, 3, 5, 2]`

**Output**

- answer = `8`

**Explanation**

We have the following sublists which meet the criteria:

- `[1]`
- `[1, 3]`
- `[1, 3, 5]`
- `[1, 3, 5, 2]`
- `[3]`
- `[3, 5]`
- `[5]`
- `[2]`

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Number-of-Sublists-With-Small-Left-Value.py"></script>
