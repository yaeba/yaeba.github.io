---
title: "Area Under Histogram"
---

You are given a list of integers `nums` where each number represents the height in a histogram.
Return the area of the largest rectangle that can be formed only from the bars of the histogram.

**Constraints**

- `n ≤ 100,000` where `n` is the length of `nums`.

[https://binarysearch.com/problems/Area-Under-Histogram](https://binarysearch.com/problems/Area-Under-Histogram){:target="\_blank"}

## Examples

### Example 1

**Input**

- nums = `[1, 3, 2, 5]`

**Output**

- answer = `6`

**Explanation**

`[1, 3, 2, 5]` corresponds to the following histogram:

```
      x
      x
  x   x
  x x x
x x x x
```

For the diagram above, for example, this would be `6`, representing the `2 x 3` area at the bottom right.

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Area-Under-Histogram.py"></script>
