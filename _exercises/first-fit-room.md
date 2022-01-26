---
title: "First Fit Room"
tags: ["greedy", "array"]
---

You are given a list of integers `rooms` and an integer `target`. Return the first integer in `rooms` that's `target` or larger. If there is no solution, return `-1`.

**Constraints**

- `0 ≤ n ≤ 100,000` where `n` is the length of `rooms`

[https://binarysearch.com/problems/First-Fit-Room](https://binarysearch.com/problems/First-Fit-Room){:target="\_blank"}

## Examples

### Example 1

**Input**

- rooms = `[15, 10, 30, 50, 25]`
- target = `20`

**Output**

- answer = `30`

**Explanation**

`30` is the first room that's at least as large as `20`.

### Example 2

**Input**

- rooms = `[15, 10, 30, 50, 25]`
- target = `51`

**Output**

- answer = `-1`

**Explanation**

There's no room that's at least `51`.

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=First-Fit-Room.java"></script>
