---
title: "Profitable Job Matching"
tags: ["array", "two pointers"]
---

You are given lists of integers `people`, `jobs`, `profits`. Each person `i` in `people` have `people[i]` amount of strength, and performing job `j` requires `jobs[j]` amount of strength and nets `profits[j]` amount of profit.

Given that each person can perform at most one job, although a job can be assigned to more than one person, return the maximum amount of profit we can attain.

**Constraints**

- `n ≤ 100,000` where `n` is the length of `people`
- `m ≤ 100,000` where `m` is the length of `jobs` and `profits`

[https://binarysearch.com/problems/Profitable-Job-Matching](https://binarysearch.com/problems/Profitable-Job-Matching){:target="\_blank"}

## Examples

### Example 1

**Input**

- people = `[5, 7, 8]`
- jobs = `[6, 5, 8]`
- profits = `[1, 2, 3]`

**Output**

- answer = `7`

**Explanation**

- First person can take the second job for profit of `2`
- Second person can take the second job for profit of `2`
- Last person can take the last job for profit of `3`

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Profitable-Job-Matching.py"></script>
