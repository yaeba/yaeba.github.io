---
title: "Unique Fractions"
---

You are given a list of lists `fractions` where each list contains `[numerator, denominator]` which represents the number `numerator / denominator`.

Return a new list of lists such that the numbers in `fractions` are:

- In their most reduced terms. E.g. `8 / 6` becomes `4 / 3`.
- Any duplicate fractions that represent the same value are removed.
- Sorted in ascending order by their value.
- If the number is negative, the `-` sign should go to the `numerator` (the input also follows this).

**Constraints**

- `n ≤ 100,000` where `n` is the length of `fractions`

[https://binarysearch.com/problems/Unique-Fractions](https://binarysearch.com/problems/Unique-Fractions){:target="\_blank"}

## Examples

### Example 1

**Input**

- fractions =

```
[[ 8, 4],
 [ 2, 1],
 [ 7, 3],
 [14, 6],
 [10, 2],
 [-3, 6]]
```

**Output**

- answer = `[[-1, 2], [2, 1], [7, 3], [5, 1]]`

**Explanation**

Once we reduce the numbers they become `[[2, 1], [2, 1], [7, 3], [7, 3], [5, 1], [-1, 2]]`. The result then comes from deduping and sorting by value.

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Unique-Fractions.py"></script>
