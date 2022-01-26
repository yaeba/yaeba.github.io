---
title: "Pascal's Triangle"
---

Given an integer `n`, return the `nth` (0-indexed) row of Pascal's triangle.

Pascal's triangle can be created as follows: In the top row, there is an array of 1. Each subsequent row is created by adding the number above and to the left with the number above and to the right, treating empty elements as `0`.

The first few rows are:

![](https://wikimedia.org/api/rest_v1/media/math/render/svg/23050fcb53d6083d9e42043bebf2863fa9746043)

[https://binarysearch.com/problems/Pascal's-Triangle](https://binarysearch.com/problems/Pascal's-Triangle){:target="\_blank"}

## Examples

### Example 1

**Input**

- n = `3`

**Output**

- answer = `[1, 3, 3, 1]`

**Explanation**

This is row `3` in

```
[1]
[1, 1]
[1, 2, 1]
[1, 3, 3, 1]
```

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Pascal's-Triangle.cpp"></script>
