---
title: "Zipped Iterator"
tags: ["data structure"]
---

Implement a zip iterator of two lists of integers `a` and `b` where

- `next()` polls the next element in the iterator, alternating between `a` and `b`
- `hasnext()` which returns whether the next element exists

**Constraints**

- `n ≤ 100,000` where `n` is the number of calls to `next` and `hasnext`

[https://binarysearch.com/problems/Zipped-Iterator](https://binarysearch.com/problems/Zipped-Iterator){:target="\_blank"}

## Examples

### Example 1

**Input**

- methods = `['constructor', 'hasnext', 'next', 'next', 'next', 'next', 'next', 'hasnext']`
- arguments = `[[[1, 2], [3, 4, 5]], [], [], [], [], [], [], []]`

**Output**

- answer = `[None, True, 1, 3, 2, 4, 5, False]`

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Zipped-Iterator.cpp"></script>
