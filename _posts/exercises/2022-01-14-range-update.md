---
title: "Range Update"
tags: ["array", "prefix sum"]
---

You are given a list of integers `nums` and a two-dimensional list of integers `operations`. Each operation is of the following form: `[L, R, X]`, which means that you should increment by `X` all the elements from indices `L` to `R` inclusive in the list (the list is 0-indexed).

Apply all operations and return the final list.

**Constraints**

- `n ≤ 10,000` where `n` is length of `nums`
- `o ≤ 10,000` where `o` is length of `operations`

[https://binarysearch.com/problems/Range-Update](https://binarysearch.com/problems/Range-Update){:target="\_blank"}

## Examples

### Example 1

**Input**

- nums = `[7, 3, 1, -10, 3]`
- operations =

```
[[0,0,3],
 [1,3,2],
 [2,3,5]]
```

**Output**

- answer = `[10, 5, 8, -3, 3]`

**Explanation**

The initial list is `[7, 3, 1, -10, 3]`.

- After applying the first operation (`[0, 0, 3]`) the list becomes `[10, 3, 1, -10, 3]`.
- After applying the second operation (`[1, 3, 2]`) the list becomes `[10, 5, 3, -8, 3]`.
- After applying the third operation (`[2, 3, 5]`) the list becomes `[10, 5, 8, -3, 3]`.

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Range-Update.py"></script>
