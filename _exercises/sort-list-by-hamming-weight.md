---
title: "Sort List by Hamming Weight"
---

You are given a lists of non-negative integers `nums`. Sort the list in ascending order by the number of `1`s in binary representation for each number. If there are ties in the number of `1`s, then break ties by their value in ascending order.

**Constraints**

- `0 ≤ n ≤ 100,000` where `n` is the length of `nums`

[https://binarysearch.com/problems/Sort-List-by-Hamming-Weight](https://binarysearch.com/problems/Sort-List-by-Hamming-Weight){:target="\_blank"}

## Examples

### Example 1

**Input**

- nums = `[3, 1, 4, 7]`

**Output**

- answer = `[1, 4, 3, 7]`

**Explanation**

`1` and `4` both have one `1`s but `1` comes earlier since it has lower value. `3` has two `1`s. And `7` has three `1`s.

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Sort-List-by-Hamming-Weight.py"></script>
