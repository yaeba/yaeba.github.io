---
title: "XOR Range Queries"
tags: ["array", "bit manipulation"]
---

You are given a list of integers `nums` and a two-dimensional list of integers `queries`. Each element in `queries` contains `[i, j]` and asks what is the value of `nums[i] ^ nums[i + 1] ^ ... ^ nums[j]`. Return a list containing the answer for each query.

**Constraints**

- `i ≤ j`
- `0 ≤ n ≤ 100,000` where `n` is the length of `nums`
- `0 ≤ m ≤ 100,000` where `m` is the length of `queries`

[https://binarysearch.com/problems/XOR-Range-Queries](https://binarysearch.com/problems/XOR-Range-Queries){:target="\_blank"}

## Examples

### Example 1

**Input**

- nums = `[1, 3, 4, 2]`
- queries =

```
[[0,1],
 [1,3]]
```

**Output**

- answer = `[2, 5]`

**Explanation**

First query asks `1 ^ 3` which is `2`. The second query asks `3 ^ 4 ^ 2` which is `5`

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=XOR-Range-Queries.py"></script>
