---
title: "Run-Length Decoded String Iterator"
tags: ["data structure", "string"]
---

Given a run-length encoded lowercase alphabet string `s`, implement an iterator which is the decoded version of `s`:

- `next()` polls the next element in the iterator
- `hasnext()` which returns whether the next element exists

**Constraints**

- `n ≤ 100,000` where `n` is the number of calls to `next` and `hasnext`

[https://binarysearch.com/problems/Run-Length-Decoded-String-Iterator](https://binarysearch.com/problems/Run-Length-Decoded-String-Iterator){:target="\_blank"}

## Examples

### Example 1

**Input**

- methods = `['constructor', 'next', 'hasnext', 'next', 'next', 'hasnext']`
- arguments = `[['2a1b'], [], [], [], [], []]`

**Output**

- answer = `[None, 'a', True, 'a', 'b', False]`

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Run-Length-Decoded-String-Iterator.cpp"></script>
