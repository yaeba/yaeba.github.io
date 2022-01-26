---
title: "Remove Half of the List"
---

Given a list of integers `nums`, consider an operation where you pick any number `e` and remove every number in `nums` equal to `e`. Return the minimum number of operations required such that the length of `nums` is reduced by at least half.

**Constraints**

- `1 ≤ n ≤ 100,000` where `n` is the length of `nums`

[https://binarysearch.com/problems/Remove-Half-of-the-List](https://binarysearch.com/problems/Remove-Half-of-the-List){:target="\_blank"}

## Examples

### Example 1

**Input**

- nums = `[1, 2, 3, 4, 5, 6]`

**Output**

- answer = `3`

**Explanation**

We can delete any `3` numbers in the list.

### Example 2

**Input**

- nums = `[7, 9, 9, 7, 3, 4, 5]`

**Output**

- answer = `2`

**Explanation**

Length of the list is `7`, so we need to remove at least `4` elements. We can do this by removing all `7`s and `9`s.

### Example 3

**Input**

- nums = `[6, 6, 6, 3, 2, 1]`

**Output**

- answer = `1`

**Explanation**

Length of the list is `6`, so we need to remove at least `3` elements. We can do this by removing all `6`s.

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Remove-Half-of-the-List.py"></script>
