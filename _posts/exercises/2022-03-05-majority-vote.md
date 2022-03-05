---
title: "Majority Vote"
tags: ["divide and conquer"]
---

You are given a list of integers `nums` containing `n` integers, where each number represents a vote to a candidate.

Return the id of the candidate that has $$\gt \lfloor \frac{n}{2}\rfloor $$ votes. If there's not a majority vote, return `-1`.

This should be done in $$\mathcal{O}(1)$$ space.

**Constraints**

- `n ≤ 100,000`

[https://binarysearch.com/problems/Majority-Vote](https://binarysearch.com/problems/Majority-Vote){:target="\_blank"}

## Examples

### Example 1

**Input**

- nums = `[5, 5, 1, 1, 2, 2, 2, 2, 2]`

**Output**

- answer = `2`

### Example 2

**Input**

- nums = `[3, 3, 4, 4]`

**Output**

- answer = `-1`

**Explanation**

Neither `3` or `4` have more than `2` votes.

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Majority-Vote.cpp"></script>
