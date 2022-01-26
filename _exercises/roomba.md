---
title: "Roomba"
---

A Roomba robot is currently sitting in a Cartesian plane at `(0, 0)`. You are given a list of its `moves` that it will make, containing `NORTH`, `SOUTH`, `WEST`, and `EAST`.

Return whether after its moves it will end up in the coordinate `(x, y)`.

**Constraints**

- `n ≤ 100,000` where `n` is length of `moves`

[https://binarysearch.com/problems/Roomba](https://binarysearch.com/problems/Roomba){:target="\_blank"}

## Examples

### Example 1

**Input**

- moves = `['WEST', 'EAST']`
- x = `1`
- y = `0`

**Output**

- answer = `False`

**Explanation**

This Roomba will end up at `(0, 0)`

### Example 2

**Input**

- moves = `['NORTH', 'EAST']`
- x = `1`
- y = `1`

**Output**

- answer = `True`

**Explanation**

Moving north moves it to `(0, 1)` and moving east moves it to `(1, 1)`

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Roomba.py"></script>
