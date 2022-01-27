---
title: "Making List Values Equal"
---

You are given a list of integers `nums`. Consider an operation where we select some subset of integers in the list and increment all of them by one.

Return the minimum number of operations needed to make all values in the list equal to each other.

**Constraints**

- `1 ≤ n ≤ 100,000` where `n` is the length of `nums`
- `0 ≤ nums[i] ≤ 10**9` for all `0 ≤ i < n`

[https://binarysearch.com/problems/Making-List-Values-Equal](https://binarysearch.com/problems/Making-List-Values-Equal){:target="\_blank"}

## Examples

### Example 1

**Input**

- nums = `[1, 3, 0]`

**Output**

- answer = `3`

**Explanation**

The 3 operations we can take are:

- Increment `[1, 0]` to get `[2, 3, 1]`
- Increment `[2, 1]` to get `[3, 3, 2]`
- Increment `[2]` to get `[3, 3, 3]`

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Making-List-Values-Equal.cpp"></script>
