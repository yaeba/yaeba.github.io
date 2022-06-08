---
title: "Minimize Number of Unique Integers After Removals"
tags: ['hash table', 'heap']
---

You are given a list of integers `nums` and an integer `n`. Given you must remove exactly `n` numbers, return the least number of unique integers after the removals.

**Constraints**
- `n ≤ 100,000` where `n` is the length of `items`

[https://binarysearch.com/problems/Minimize-Number-of-Unique-Integers-After-Removals](https://binarysearch.com/problems/Minimize-Number-of-Unique-Integers-After-Removals){:target="\_blank"}



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

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Minimize-Number-of-Unique-Integers-After-Removals.py"></script>

