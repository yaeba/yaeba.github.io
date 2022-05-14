---
title: "Stack Sequence"
tags: ["stack"]
---

Given a list of distinct integers `pushes`, and another list of integers `pops`, return whether this is a valid sequence of stack push and pop actions.

**Constraints**

- `n ≤ 100,000` where `n` is the length of `pushes`
- `m ≤ 100,000` where `m` is the length of `pops`

[https://binarysearch.com/problems/Stack-Sequence](https://binarysearch.com/problems/Stack-Sequence){:target="\_blank"}

## Examples

### Example 1

**Input**

- pushes = `[0, 1, 4, 6, 8]`
- pops = `[1, 0, 8, 6, 4]`

**Output**

- answer = `True`

**Explanation**

We can first push `[0, 1]`, then pop both off. Then push `[4, 6, 8]` and then pop them all off.

### Example 2

**Input**

- pushes = `[1, 2, 3, 4]`
- pops = `[4, 1, 2, 3]`

**Output**

- answer = `False`

**Explanation**

This is not valid since `3` was pushed after `1` but is popped earlier.

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Stack-Sequence.py"></script>
