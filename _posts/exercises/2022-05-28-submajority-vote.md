---
title: "Submajority Vote"
tags: ["array"]
---

You are given a list of integers `nums` where each number represents a vote to a candidate.

Return the ids of the candidates that have greater than $$\lfloor \frac{n}{3}\rfloor $$ votes, in ascending order.

Bonus: solve in $$\mathcal{O}(1)$$ space.

**Constraints**

- `n ≤ 100,000` where `n` is the length of `nums`.

[https://binarysearch.com/problems/Submajority-Vote](https://binarysearch.com/problems/Submajority-Vote){:target="\_blank"}

## Examples

### Example 1

**Input**

- nums = `[1, 1, 1, 1, 2, 3]`

**Output**

- answer = `[1]`

### Example 2

**Input**

- nums = `[2, 1, 5, 5, 5, 5, 6, 6, 6, 6, 6]`

**Output**

- answer = `[5, 6]`

**Explanation**

Both `5` and `6` have `40`% of the votes.

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Submajority-Vote.cpp"></script>
