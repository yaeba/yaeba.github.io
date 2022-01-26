---
title: "Target Number with Operations"
---

Given positive integers `start` and `end` (`start < end`), return the minimum number of operations needed to convert `start` to `end` using these operations:

- Increment by `1`
- Multiply by `2`

**Constraints**

- `start < end < 2 ** 31`

[https://binarysearch.com/problems/Target-Number-with-Operations](https://binarysearch.com/problems/Target-Number-with-Operations){:target="\_blank"}

## Examples

### Example 1

**Input**

- start = `2`
- end = `9`

**Output**

- answer = `3`

**Explanation**

We can multiply `2` to get `4`, and then again to get `8`, then add `1` to get `9`.

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Target-Number-with-Operations.cpp"></script>
