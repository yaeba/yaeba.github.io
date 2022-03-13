---
title: "Packing Boxes"
tags: ["array"]
---

Given a list of integers `nums`, pack consecutive elements of the same value into sublists.

Note: If there's only one occurrence in the list it should still be in its own sublist.

**Constraints**

- `0 ≤ n ≤ 100,000` where `n` is the length of `nums`

[https://binarysearch.com/problems/Packing-Boxes](https://binarysearch.com/problems/Packing-Boxes){:target="\_blank"}

## Examples

### Example 1

**Input**

- nums = `[5, 5, 5, 5, 5, 5, 5, 5]`

**Output**

- answer = `[[5, 5, 5, 5, 5, 5, 5, 5]]`

### Example 2

**Input**

- nums = `[1]`

**Output**

- answer = `[[1]]`

### Example 3

**Input**

- nums = `[4, 4, 1, 6, 6, 6, 1, 1, 1, 1]`

**Output**

- answer = `[[4, 4], [1], [6, 6, 6], [1, 1, 1, 1]]`

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Packing-Boxes.cpp"></script>
<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Packing-Boxes.py"></script>
