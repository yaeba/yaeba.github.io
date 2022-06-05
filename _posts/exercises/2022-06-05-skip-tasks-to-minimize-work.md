---
title: "Skip Tasks to Minimize Work"
tags: ["dynamic programming"]
---

You are given a list of integers nums representing tasks that you must get through in order. Each value represents the amount of time it takes to finish that task. Given that you can skip tasks as long as you don’t skip twice in a row, return the minimum time it takes to get through all the tasks.

**Constraints**

- `n ≤ 100,000` where `n` is the length of `nums`.

[https://binarysearch.com/problems/Skip-Tasks-to-Minimize-Work](https://binarysearch.com/problems/Skip-Tasks-to-Minimize-Work){:target="\_blank"}

## Examples

### Example 1

**Input**

- nums = `[10, 5, 7, 15]`

**Output**

- answer = `12`

**Explanation**

We can skip the first and last tasks.

### Example 2

**Input**

- nums = `[10, 20]`

**Output**

- answer = `10`

**Explanation**

We can skip the last task.

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Skip-Tasks-to-Minimize-Work.py"></script>
