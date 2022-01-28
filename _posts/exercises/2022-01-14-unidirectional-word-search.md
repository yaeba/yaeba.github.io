---
title: "Unidirectional Word Search"
tags: ["array"]
---

Given a two-dimensional matrix of characters `board` and a string `target`, return whether the `target` can be found in the matrix by going left-to-right, or up-to-down unidirectionally.

**Constraints**

- `n, m ≤ 250` where `n` is the number of rows and columns in `board`
- `k ≤ 250` where `k` is the length of `word`

[https://binarysearch.com/problems/Unidirectional-Word-Search](https://binarysearch.com/problems/Unidirectional-Word-Search){:target="\_blank"}

## Examples

### Example 1

**Input**

- board = `[['H', 'E', 'L', 'L', 'O'], ['A', 'B', 'C', 'D', 'E']]`
- word = `HELLO`

**Output**

- answer = `True`

### Example 2

**Input**

- board = `[['x', 'z', 'd', 'x'], ['p', 'g', 'u', 'x'], ['k', 'j', 'z', 'd']]`
- word = `xgz`

**Output**

- answer = `False`

**Explanation**

You can't make `"xgz"` going left-to-right or up-to-down.

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Unidirectional-Word-Search.py"></script>
