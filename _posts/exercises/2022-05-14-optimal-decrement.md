---
title: "Optimal Decrement"
---

You are given a list of integers `nums` and an integer `k`. You must subtract `1` from any element in the list `k` times. Return the minimum possible maximum value in the list after `k` operations.

**Constraints**

- `0 ≤ n, k ≤ 100,000` where `n` is the length of `nums`.
- `-10^9 ≤ nums[i] ≤ 10^9`

[https://binarysearch.com/problems/Optimal-Decrement](https://binarysearch.com/problems/Optimal-Decrement){:target="\_blank"}

## Examples

### Example 1

**Input**

- nums = `[2, 3, 5, 4]`
- k = `6`

**Output**

- answer = `2`

**Explanation**

We can decrement the following:

- Decrement `3` one time.
- Decrement `5` three times.
- Decrement `4` two times.

### Example 2

**Input**

- nums = `[5, 5, 5, 5]`
- k = `8`

**Output**

- answer = `3`

**Explanation**

We can decrement each of the `5`s twice.

### Example 3

**Input**

- nums = `[5, 5, 5, 5]`
- k = `7`

**Output**

- answer = `4`

**Explanation**

We can decrement each of the `5`s once to make them `4`. Then we can decrement three times but there's `4` numbers left, so the minimum possible maximum value would still be `4`.

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Optimal-Decrement.py"></script>
