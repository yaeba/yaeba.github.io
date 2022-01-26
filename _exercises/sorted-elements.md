---
title: "Sorted Elements"
---

Give a list of numbers `nums`, return the number of elements that are in the correct indices, if the list were to be sorted.

**Constraints**

- `n ≤ 100,000` where `n` is the length of `nums`

[https://binarysearch.com/problems/Sorted-Elements](https://binarysearch.com/problems/Sorted-Elements){:target="\_blank"}

## Examples

### Example 1

**Input**

- nums = `[1, 7, 3, 4, 10]`

**Output**

- answer = `2`

**Explanation**

Comparing `nums` and its sorted version we find that elements `1` and `10` are in their correct positions.

```
[1, 7, 3, 4, 10]
[1, 3, 4, 7, 10]
```

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Sorted-Elements.py"></script>
