---
title: "Count Next Element"
---

Given a list of integers `nums`, return the number of elements `x` there are such that `x + 1` exists as well.

**Constraints**

- `n ≤ 100,000` where `n` is the length of `nums`

[https://binarysearch.com/problems/Count-Next-Element](https://binarysearch.com/problems/Count-Next-Element){:target="\_blank"}

## Examples

### Example 1

**Input**

- nums = `[3, 1, 2, 2, 7]`

**Output**

- answer = `3`

**Explanation**

We can take

- `1` since `1 + 1` exists in the list.
- `2` since `2 + 1` exists in the list.
- Another `2`.

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Count-Next-Element.py"></script>
