---
title: "Maximum Sum Rectangle with Condition"
tags: ["queue", "prefix sum"]
---

Given a two-dimensional integer matrix `matrix` and an integer `k`, return the largest sum of a rectangle `≤ k`.

**Constraints**

- `n, m ≤ 100` where `n` and `m` are the number of rows and columns in `matrix`.

[https://binarysearch.com/problems/Maximum-Sum-Rectangle-with-Condition](https://binarysearch.com/problems/Maximum-Sum-Rectangle-with-Condition){:target="\_blank"}

## Examples

### Example 1

**Input**

- matrix =

```
[[ 2,-2],
 [ 3, 2]]
```

- k = `6`

**Output**

- answer = `5`

**Explanation**

We can take the rectangle `[2, 3]` to get sum of `5`.

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Maximum-Sum-Rectangle-with-Condition.py"></script>
