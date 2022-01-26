---
title: "Two-Dimensional List Iterator"
tags: ["data structure"]
---

Implement an iterator of two-dimensional list of integers `lists`.

- `next()` polls the next element in the iterator, iterating over each row in `lists`
- `hasnext()` which returns whether the next element exists

For example:

```
it = TwoDimensionalIterator([[1, 2],[3, 4],[5]])
it.next() == 1
it.next() == 2
it.next() == 3
it.hasnext() == True
it.next() == 4
it.next() == 5
it.hasnext() == False
```

**Constraints**

- `n ≤ 100,000` where `n` is the number of calls to `next` and `hasnext`

**Notes**

- Your iterator should use $$\mathcal{O}(1)$$ extra space.

[https://binarysearch.com/problems/Two-Dimensional-List-Iterator](https://binarysearch.com/problems/Two-Dimensional-List-Iterator){:target="\_blank"}

## Examples

### Example 1

**Input**

- methods = `['constructor', 'next', 'next', 'next', 'hasnext', 'next', 'next', 'hasnext']`
- arguments = `[[[[1, 2], [3, 4], [5]]], [], [], [], [], [], [], []]`

**Output**

- answer = `[None, 1, 2, 3, True, 4, 5, False]`

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Two-Dimensional-List-Iterator.py"></script>
