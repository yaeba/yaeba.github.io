---
title: "In-Place Move Zeros to End of List"
tags: ["two pointers", "array"]
---

Given a list of integers `nums`, put all the zeros to the back of the list by modifying the list in-place. The relative ordering of other elements should stay the same.

Can you do it in $$\mathcal{O}(1)$$ additional space?

**Constraints**

- `0 ≤ n ≤ 100,000` where `n` is the length of `nums`

[https://binarysearch.com/problems/In-Place-Move-Zeros-to-End-of-List](https://binarysearch.com/problems/In-Place-Move-Zeros-to-End-of-List){:target="\_blank"}

## Examples

### Example 1

**Input**

- nums = `[0, 1, 0, 2, 3]`

**Output**

- answer = `[1, 2, 3, 0, 0]`

**Explanation**

Note that `[1, 2, 3]` appear in the same order as in the input.

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=In-Place-Move-Zeros-to-End-of-List.cpp"></script>
