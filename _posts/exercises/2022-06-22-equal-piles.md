---
title: "Equal Piles"
---

Given a list of integers `nums`, you can perform the following operation: pick the largest integer in `nums` and turn it into the second largest number.

Return the minimum number of operations required to make all integers the same in the list.

**Constraints**

- `n ≤ 100,000` where `n` is the length of `nums`

[https://binarysearch.com/problems/Equal-Piles](https://binarysearch.com/problems/Equal-Piles){:target="\_blank"}

## Examples

### Example 1

**Input**

- nums = `[4, 8, 2]`

**Output**

- answer = `3`

**Explanation**

- Turn `8` to `4` to get `[4, 4, 2]`
- Turn `4` to `2` to get `[2, 4, 2]`
- Turn `4` to `2` to get `[2, 2, 2]`

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Equal-Piles.py"></script>
