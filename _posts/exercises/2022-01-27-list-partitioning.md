---
title: "List Partitioning"
tags: ["two pointers", "array", "hash table"]
---

Given a list of strings `strs`, containing the strings `"red"`, `"green"` and `"blue"`, partition the list so that the red come before green, which come before blue.

This should be done in $$\mathcal{O}(n)$$ time.

Bonus: Can you do it in $$\mathcal{O}(1)$$ space? That is, can you do it by only rearranging the list (i.e. without creating any new strings)?

**Constraints**

- `n ≤ 100,000` where `n` is the length of `strs`.

[https://binarysearch.com/problems/List-Partitioning](https://binarysearch.com/problems/List-Partitioning){:target="\_blank"}

## Examples

### Example 1

**Input**

- strs = `['green', 'blue', 'red', 'red']`

**Output**

- answer = `['red', 'red', 'green', 'blue']`

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=List-Partitioning.cpp"></script>
