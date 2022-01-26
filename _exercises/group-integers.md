---
title: "Group Integers"
---

Given a list of integers `nums`, return whether you can split the list into `1` or more groups where:

- The size of each group is larger than or equal to `2`.
- The sizes of all groups are equal.
- All the integers in each group are the same.

**Constraints**

- `n ≤ 100,000` where `n` is the length of `nums`

[https://binarysearch.com/problems/Group-Integers](https://binarysearch.com/problems/Group-Integers){:target="\_blank"}

## Examples

### Example 1

**Input**

- nums = `[2, 3, 5, 8, 3, 2, 5, 8]`

**Output**

- answer = `True`

**Explanation**

We can group the numbers like so:

- `[2, 2]`
- `[3, 3]`
- `[5, 5]`
- `[8, 8]`

### Example 2

**Input**

- nums = `[3, 0, 0, 3, 3, 3]`

**Output**

- answer = `True`

**Explanation**

We can group the numbers like so:

- `[0, 0]`
- `[3, 3]`
- `[3, 3]`

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Group-Integers.py"></script>
