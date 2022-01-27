---
title: "Unobstructed Buildings"
tags: ["stack"]
---

You are given a list of integers `heights` representing building heights. A building `heights[i]` can see the ocean if every building on its right has shorter height. Return the building indices where you can see the ocean, in ascending order.

**Constraints**

- `0 ≤ n ≤ 100,000` where `n` is the length of `heights`

[https://binarysearch.com/problems/Unobstructed-Buildings](https://binarysearch.com/problems/Unobstructed-Buildings){:target="\_blank"}

## Examples

### Example 1

**Input**

- heights = `[1, 5, 5, 2, 3]`

**Output**

- answer = `[2, 4]`

**Explanation**

We can see the ocean in building `heights[2]` and `heights[4]`.

### Example 2

**Input**

- heights = `[1, 1, 1, 1, 1]`

**Output**

- answer = `[4]`

**Explanation**

We can't see the ocean in any building other than the last one.

### Example 3

**Input**

- heights = `[5, 4, 3, 2, 1]`

**Output**

- answer = `[0, 1, 2, 3, 4]`

**Explanation**

We can see the ocean in every building since each building is taller than every other on its right.

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Unobstructed-Buildings.cpp"></script>
