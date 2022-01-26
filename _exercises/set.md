---
title: "Set"
tags: ["data structure"]
---

Implement a set data structure with the following methods:

- `CustomSet()` constructs a new instance of a set
- `add(int val)` adds `val` to the set
- `exists(int val)` returns whether `val` exists in the set
- `remove(int val)` removes the `val` in the set

This should be implemented without using built-in set.

**Constraints**

- `n ≤ 100,000` where `n` is the number of calls to `add`, `exists` and `remove`

[https://binarysearch.com/problems/Set](https://binarysearch.com/problems/Set){:target="\_blank"}

## Examples

### Example 1

**Input**

- methods = `['constructor', 'add', 'exists', 'remove', 'exists']`
- arguments = `[[], [1], [1], [1], [1]]`

**Output**

- answer = `[None, None, True, None, False]`

**Explanation**

```
c = CustomSet()
c.add(1)
c.exists(1) == True
c.remove(1)
c.exists(1) == False
```

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Set.cpp"></script>
