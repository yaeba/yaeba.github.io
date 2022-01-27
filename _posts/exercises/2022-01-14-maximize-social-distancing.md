---
title: "Maximize Social Distancing"
tags: ["array"]
---

You are given a list of integers `seats` containing `1`s and `0`s. Each element `seats[i]` represents a seat and is either occupied if `seats[i] = 1` or empty if `seats[i] = 0`.

Given that there’s at least one empty seat and at least one occupied seat, return the maximum distance from an empty seat to the closest occupied seat.

**Constraints**

- `n ≤ 100,000` where `n` is the length of `seats`

[https://binarysearch.com/problems/Maximize-Social-Distancing](https://binarysearch.com/problems/Maximize-Social-Distancing){:target="\_blank"}

## Examples

### Example 1

**Input**

- seats = `[1, 0, 1, 0, 0, 0, 1]`

**Output**

- answer = `2`

**Explanation**

We can sit at `seats[4]`.

### Example 2

**Input**

- seats = `[1, 0, 0, 0]`

**Output**

- answer = `3`

**Explanation**

We can sit at `seats[3]`.

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Maximize-Social-Distancing.cpp"></script>
<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Maximize-Social-Distancing.py"></script>
