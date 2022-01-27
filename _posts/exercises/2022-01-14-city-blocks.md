---
title: "City Blocks"
tags: ["hash table"]
---

You are given a two-dimensional `matrix` of unique strings representing city blocks, and a list of strings `blocks` to visit. Given that you are sitting at block `matrix[0][0]`, return the total Manhattan distance required to visit every block in order.

**Constraints**

- `0 ≤ n * m ≤ 100,000` where `n` and `m` are the number of rows and columns in `matrix`

[https://binarysearch.com/problems/City-Blocks](https://binarysearch.com/problems/City-Blocks){:target="\_blank"}

## Examples

### Example 1

**Input**

- matrix = `[['a', 'b', 'c'], ['d', 'e', 'f'], ['g', 'h', 'i']]`
- blocks = `['h', 'b', 'c']`

**Output**

- answer = `6`

**Explanation**

- "h" is `2` blocks south and `1` block east.
- "b" is `2` blocks north.
- "c" is `1` block east.

Which adds up to 6.

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=City-Blocks.py"></script>
