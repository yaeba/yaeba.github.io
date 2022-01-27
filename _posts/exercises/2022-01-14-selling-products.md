---
title: "Selling Products"
tags: ["hash table", "heap"]
---

You are given a list of integers `items` and an integer `n`. A salesperson has `items` in a bag with random IDs. The salesperson can remove as many as `n` items from the bag. Determine the minimum number of different IDs the final bag can contain after performing, at most `n` deletions.

**Constraints**

- `n ≤ 100,000` where `n` is the length of `items`

[https://binarysearch.com/problems/Selling-Products](https://binarysearch.com/problems/Selling-Products){:target="\_blank"}

## Examples

### Example 1

**Input**

- items = `[1, 1, 1, 0, 0]`
- n = `2`

**Output**

- answer = `1`

**Explanation**

We can delete the two `0`s to get `1`s. Then there's only `1` unique ID left.

### Example 2

**Input**

- items = `[0, 0, 1, 1, 2, 3]`
- n = `2`

**Output**

- answer = `2`

**Explanation**

We can delete the `2` and the `3` to get `[0, 0, 1, 1]`. Then there's only `2` unique ID left.

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Selling-Products.py"></script>
