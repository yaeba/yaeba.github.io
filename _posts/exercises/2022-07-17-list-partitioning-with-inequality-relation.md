---
title: "List Partitioning with Inequality Relation"
tags: ["array"]
---

Given a list of integers `nums`, we want to split the list into two non-empty sublists `a` and `b` such that every element in `a` is less than or equal to every element in `b`.

Return the smallest length of `a` that is possible. You can assume that the solution exists.

**Constraints**

- `n ≤ 100,000` where `n` is the length of `nums`

[https://binarysearch.com/problems/List-Partitioning-with-Inequality-Relation](https://binarysearch.com/problems/List-Partitioning-with-Inequality-Relation){:target="\_blank"}

## Examples

### Example 1

**Input**

- nums = `[2, 0, 1, 4, 3]`

**Output**

- answer = `3`

**Explanation**

We can split the list into `a = [2, 0, 1]` and `b = [4, 3]`.

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=List-Partitioning-with-Inequality-Relation.py"></script>
