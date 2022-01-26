---
title: "Hash Table"
tags: ["hash table"]
---

Implement a hash table with the following methods:

- `HashTable()` constructs a new instance of a hash table
- `put(int key, int val)` updates the hash table such that `key` maps to `val`
- `get(int key)` returns the value associated with `key`. If there is no such `key`, then return `-1`.
- `remove(int key)` removes both the `key` and the value associated with it in the hash table.

This should be implemented without using built-in hash table.

**Constraints**

- `n ≤ 100,000` where `n` is the number of calls to `put`, `get` and `remove`

[https://binarysearch.com/problems/Hash-Table](https://binarysearch.com/problems/Hash-Table){:target="\_blank"}

## Examples

### Example 1

**Input**

- methods = `['constructor', 'put', 'get', 'remove', 'get']`
- arguments = `[[], [1, 10], [1], [1], [1]]`

**Output**

- answer = `[None, None, 10, None, -1]`

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Hash-Table.cpp"></script>
