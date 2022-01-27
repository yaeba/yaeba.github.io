---
title: "Lexicographically Largest Mountain List"
tags: ["array"]
---

You are given three positive integers `n`, `lower`, and `upper`. You want to create a list of length `n` that is strictly increasing and then strictly decreasing and all the numbers are between `[lower, upper]`, inclusive. Each of the increasing and decreasing parts should be non-empty.

Return the lexicographically largest list possible, or the empty list if it's not possible.

**Constraints**

- `3 ≤ n ≤ 100,000`
- `1 ≤ lower ≤ upper < 2 ** 31`

[https://binarysearch.com/problems/Lexicographically-Largest-Mountain-List](https://binarysearch.com/problems/Lexicographically-Largest-Mountain-List){:target="\_blank"}

## Examples

### Example 1

**Input**

- n = `5`
- lower = `2`
- upper = `6`

**Output**

- answer = `[5, 6, 5, 4, 3]`

**Explanation**

Note that `[6, 5, 4, 3, 2]` is not valid since the strictly increasing part has to be non-empty.

### Example 2

**Input**

- n = `5`
- lower = `90`
- upper = `92`

**Output**

- answer = `[90, 91, 92, 91, 90]`

### Example 3

**Input**

- n = `6`
- lower = `3`
- upper = `5`

**Output**

- answer = `[]`

**Explanation**

It's impossible to make a strictly increasing then decreasing list of size `6` here.

### Example 4

**Input**

- n = `3`
- lower = `8`
- upper = `11`

**Output**

- answer = `[10, 11, 10]`

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Lexicographically-Largest-Mountain-List.java"></script>
