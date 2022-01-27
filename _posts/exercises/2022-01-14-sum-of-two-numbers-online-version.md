---
title: "Sum of Two Numbers - Online Version"
tags: ["data structure"]
---

Implement a data structure with the following methods:

- `add(int val)` adds the value `val` to the data structure
- `find(int val)` returns whether there are two elements whose sum equals to `val`

**Constraints**

- `n ≤ 10,000` where `n` is the number of times `add` will be called
- `m ≤ 1,000` where `m` is the number of times `find` will be called

[https://binarysearch.com/problems/Sum-of-Two-Numbers-Online-Version](https://binarysearch.com/problems/Sum-of-Two-Numbers-Online-Version){:target="\_blank"}

## Examples

### Example 1

**Input**

- methods = `['constructor', 'add', 'find', 'add', 'find']`
- arguments = `[[], [5], [10], [6], [11]]`

**Output**

- answer = `[None, None, False, None, True]`

**Explanation**

- We create a `TwoSum` first
- Then we add the number `5` to the data structure
- We check if there's two numbers whose sum is `10`. There isn't, so we return `false`
- Then we add the number `6` to the data structure
- We check if there's two numbers whose sum is `11`, which there is since `5 + 6 = 11`.

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Sum-of-Two-Numbers-Online-Version.cpp"></script>
