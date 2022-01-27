---
title: "Range Query on a List"
tags: ["array", "data structure", "prefix sum"]
---

Implement a data structure with the following methods:

- `RangeSum(int[] nums)` constructs a new instance with the given `nums`.
- `total(int i, int j)` returns the sum of integers from `nums` between `[i, j)`. That is, `nums[i] + nums[i + 1] + ... + nums[j - 1]`.

**Constraints**

- `n ≤ 100,000` where `n` is the length of `nums`
- `k ≤ 100,000` where `k` is the number of calls to `total`

[https://binarysearch.com/problems/Range-Query-on-a-List](https://binarysearch.com/problems/Range-Query-on-a-List){:target="\_blank"}

## Examples

### Example 1

**Input**

- methods = `['constructor', 'total', 'total']`
- arguments = `[[[1, 2, 5, 0, 3, 7]], [0, 3], [1, 5]]`

**Output**

- answer = `[None, 8, 10]`

**Explanation**

```
r = RangeSum([1,2,5,0,3,7])
r.total(0, 3) == 8 # sum([1, 2, 5])
r.total(1, 5) == 10 # sum([2, 5, 0, 3])
```

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Range-Query-on-a-List.cpp"></script>
