---
title: "Binary Search Tree Iterator"
tags: ["tree", "data structure"]
---

Implement a binary search tree iterator with the following methods:

- `next` returns the next smallest element in the tree
- `hasnext` returns whether there is a next element in the iterator

For example, given the following tree

```
   4
  / \
 2   7
    / \
   5   9
```

It should return the values in this order `2`, `4`, `5`, `7`, `9`.

[https://binarysearch.com/problems/Binary-Search-Tree-Iterator](https://binarysearch.com/problems/Binary-Search-Tree-Iterator){:target="\_blank"}

## Examples

### Example 1

**Input**

- methods = `['constructor', 'hasnext', 'hasnext', 'next', 'hasnext', 'hasnext', 'hasnext', 'next', 'hasnext', 'hasnext', 'hasnext', 'next', 'hasnext', 'next', 'hasnext']`
- arguments = `[[[[2, 1, 3, 0], [1, 3, -1, -1], [2, -1, -1, -1]]], [], [], [], [], [], [], [], [], [], [], [], [], [], []]`

**Output**

- answer = `[None, True, True, 0, True, True, True, 1, True, True, True, 2, True, 3, False]`

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Binary-Search-Tree-Iterator.cpp"></script>
