---
title: "Meeting Schedule For Two People"
tags: ["line sweep"]
---

You are given two two-dimensional list of integers `a` and `b` and an integer `duration`. Each element in `a` contains an inclusive interval `[start, end]` meaning that person `a` is free during those times. `b` is in the same format and means `b` is free during those times. Intervals `a` is disjoint as is `b`.

Return the earliest time both people are free for `duration` amount of time. If there's no solution, return the empty list.

**Constraints**

- `n ≤ 100,000` where `n` is the length of `a`
- `m ≤ 100,000` where `m` is the length of `b`
- `1 ≤ duration`

[https://binarysearch.com/problems/Meeting-Schedule-For-Two-People](https://binarysearch.com/problems/Meeting-Schedule-For-Two-People){:target="\_blank"}

## Examples

### Example 1

**Input**

- a =

```
[[  1,  2],
 [  3,  7],
 [  8,100]]
```

- b =

```
[[0,1],
 [3,8]]
```

- duration = `4`

**Output**

- answer = `[3, 7]`

### Example 2

**Input**

- a =

```
[[3,9]]
```

- b =

```
[[1,2]]
```

- duration = `5`

**Output**

- answer = `[]`

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Meeting-Schedule-For-Two-People.py"></script>
