---
title: "Earliest Uniques in a Stream"
tags: ["hash table", "data structure"]
---

Implement a data structure with the following methods:

- `EarliestUnique(int[] nums)` constructs a new instance with the given list of numbers.
- `add(int num)` adds `num` to the data structure.
- `firstUnique()` returns the first unique number. If there's no unique number, return `-1`.

**Constraints**

- `n ≤ 100,000` where `n` is the number of calls to `add` and `firstUnique`.

[https://binarysearch.com/problems/Earliest-Uniques-in-a-Stream](https://binarysearch.com/problems/Earliest-Uniques-in-a-Stream){:target="\_blank"}

## Examples

### Example 1

**Input**

- methods = `['constructor', 'add', 'earliestUnique', 'add', 'earliestUnique']`
- arguments = `[[[1, 2, 3]], [1], [], [2], []]`

**Output**

- answer = `[None, None, 2, None, 3]`

**Explanation**

```
e = EarliestUnique([1, 2, 3])
e.add(1)
e.earliestUnique() == 2
e.add(2)
e.earliestUnique() == 3
```

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Earliest-Uniques-in-a-Stream.py"></script>
