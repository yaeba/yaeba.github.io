---
title: "Peekable Iterator"
tags: ["data structure"]
---

Implement an iterator of a list of integers `nums` where

- `peek()` returns the next element, without moving the iterator
- `next()` polls the next element in the iterator
- `hasnext()` which returns whether the next element exists

**Constraints**

- `n ≤ 100,000` where `n` is the number of calls to `peek`, `next` and `hasnext`

[https://binarysearch.com/problems/Peekable-Iterator](https://binarysearch.com/problems/Peekable-Iterator){:target="\_blank"}

## Examples

### Example 1

**Input**

- methods = `['constructor', 'peek', 'next', 'hasnext', 'peek', 'next', 'hasnext']`
- arguments = `[[[1, 2]], [], [], [], [], [], []]`

**Output**

- answer = `[None, 1, 1, True, 2, 2, False]`

**Explanation**

- First we create a `PeekableIterator` with values `[1, 2]`
- We peek the next element which is `1`
- We poll the next element which is `1`
- We check if the next element exists, which it does since `2` is next in the iterator.
- We peek the next element which is `2`
- We poll the next element which is `2`
- We check if the next element exists which it doesn't

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Peekable-Iterator.py"></script>
