---
title: "Bomber Man"
tags: ["hash table"]
---

You are given a two-dimensional integer `matrix` of `1`s and `0`s, where a `1` represents a bomb and `0` represents an empty cell. When a bomb explodes, all the spaces along on the same row and column are damaged. Return the number of spaces you can stand in to not get damaged.

**Constraints**

- `n * m ≤ 200,000` where `n` and `m` are the number of rows and columns in `matrix`.

[https://binarysearch.com/problems/Bomber-Man](https://binarysearch.com/problems/Bomber-Man){:target="\_blank"}

## Examples

### Example 1

**Input**

- matrix = `[[1, 0, 0], [0, 1, 0], [0, 0, 0]]`

**Output**

- answer = `1`

**Explanation**

Only the bottom right cell is safe

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Bomber-Man.py"></script>
