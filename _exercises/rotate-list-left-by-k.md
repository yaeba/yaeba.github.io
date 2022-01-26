---
title: "Rotate List Left by K"
tags: ["array"]
---

Write a function that rotates a list of numbers to the left by `k` elements. Numbers should wrap around.

Note: The list is guaranteed to have at least one element, and `k` is guaranteed to be less than or equal to the length of the list.

Bonus: Do this without creating a copy of the list. How many swap or move operations do you need?

**Constraints**

- `n ≤ 100,000` where `n` is the length of `nums`

[https://binarysearch.com/problems/Rotate-List-Left-by-K](https://binarysearch.com/problems/Rotate-List-Left-by-K){:target="\_blank"}

## Examples

### Example 1

**Input**

- nums = `[1, 2, 3, 4, 5, 6]`
- k = `6`

**Output**

- answer = `[1, 2, 3, 4, 5, 6]`

**Explanation**

### Example 2

**Input**

- nums = `[1]`
- k = `0`

**Output**

- answer = `[1]`

**Explanation**

### Example 3

**Input**

- nums = `[1, 2, 3, 4, 5, 6]`
- k = `2`

**Output**

- answer = `[3, 4, 5, 6, 1, 2]`

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Rotate-List-Left-by-K.cpp"></script>
