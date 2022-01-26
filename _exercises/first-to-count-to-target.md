---
title: "First to Count to Target"
tags: ["dynamic programming", "minimax", "math"]
---

You are playing a game against a friend where in each round you pick a number from `1` to `k` to add to a shared running total that initially starts from `0`. The first person to reach or exceed the running total to `target` wins.

Given that you go first, return whether you can force a win if everyone plays optimally.

**Constraints**

- `k ≤ 30`
- `target ≤ 1,000`

[https://binarysearch.com/problems/First-to-Count-to-Target](https://binarysearch.com/problems/First-to-Count-to-Target){:target="\_blank"}

## Examples

### Example 1

**Input**

- k = `5`
- target = `9`

**Output**

- answer = `True`

**Explanation**

If we pick `3` first, then whether your friend picks `1`, `2`, ..., or `5` , we can always reach `9` by picking `5` next.

### Example 2

**Input**

- k = `3`
- target = `4`

**Output**

- answer = `False`

**Explanation**

No mater what we pick your friend can pick `3` to reach `4`.

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=First-to-Count-to-Target.cpp"></script>
