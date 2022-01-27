---
title: "Rain Catcher"
tags: ["two pointers", "array"]
---

You are given a list of non-negative integers `nums` where each element represents the height of a hill. Suppose it will rain and all the spaces between two sides get filled up.

Return the amount of rain that would be caught between the hills.

**Constraints**

- `n ≤ 100,000` where `n` is the length of `nums`

[https://binarysearch.com/problems/Rain-Catcher](https://binarysearch.com/problems/Rain-Catcher){:target="\_blank"}

## Examples

### Example 1

**Input**

- nums = `[2, 1, 2]`

**Output**

- answer = `1`

**Explanation**

We can hold 1 unit of water in middle.

### Example 2

**Input**

- nums = `[3, 0, 1, 3, 0, 5]`

**Output**

- answer = `8`

**Explanation**

We can hold 3 units in the first index, 2 in the second, and 3 in the fourth index (we cannot hold 5 since it would run off to the left), so we can catch 8 units of water.

### Example 3

**Input**

- nums = `[2, 5, 2, 0, 5, 8, 8]`

**Output**

- answer = `8`

**Explanation**

`nums[2]` can catch 3 rain drops, and `nums[3]` can catch `5` for a total of `8`.

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Rain-Catcher.py"></script>
