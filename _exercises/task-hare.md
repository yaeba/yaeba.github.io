---
title: "Task Hare"
tags: ["array"]
---

You are given a list of integers `tasks` and another list of integers `people`. The integer `tasks[i]` represents the amount of strength required to perform the `i`th task. `people[i]` represents the amount of strength the `i`th person has.

Return the number of tasks that can be finished if one person can perform at most one task.

**Constraints**

- `n ≤ 100,000` where `n` is the length of `tasks`
- `m ≤ 100,000` where `m` is the length of `people`

[https://binarysearch.com/problems/Task-Hare](https://binarysearch.com/problems/Task-Hare){:target="\_blank"}

## Examples

### Example 1

**Input**

- tasks = `[3, 2, 9, 13]`
- people = `[10, 5, 2, 1]`

**Output**

- answer = `3`

**Explanation**

- First person can perform task `9`
- Second person can perform task `3`
- Third person can perform task `2`
- Fourth person can't perform any tasks

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Task-Hare.cpp"></script>
