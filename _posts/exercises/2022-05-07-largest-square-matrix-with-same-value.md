---
title: "Largest Square Matrix with Same Value"
tags: ["dynamic programming"]
---

Given a two-dimensional list of integers `matrix`, find the largest `k × k` submatrix such that all of its elements are the same value, and return the `k`.

**Constraints**

- `n, m ≤ 250` where `n` and `m` are the number of rows and columns in `matrix`.

[https://binarysearch.com/problems/Largest-Square-Matrix-with-Same-Value](https://binarysearch.com/problems/Largest-Square-Matrix-with-Same-Value){:target="\_blank"}

## Examples

### Example 1

**Input**

- matrix =

```
[[1,1,3],
 [1,1,3],
 [5,5,5]]
```

**Output**

- answer = `2`

**Explanation**

There's a `2 × 2` square of `1`s on the top left.

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Largest-Square-Matrix-with-Same-Value.py"></script>
