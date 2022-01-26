---
title: "Virtual Boolean Array"
tags: ["hash table", "data structure"]
---

Implement a boolean array which implements the following methods:

- `BooleanArray()` which initializes an array of size `2 ** 31` with all false values.
- `void setTrue(int i)` which sets the value at index `i` to true.
- `void setFalse(int i)` which sets the value at index `i` to false.
- `void setAllTrue()` which sets the value at every index to true.
- `void setAllFalse()` which sets the value at every index to false.
- `boolean getValue(int i)` which returns the value at index `i`.

**Constraints**

- `0 ≤ n ≤ 100,000` where `n` is the number of method calls

[https://binarysearch.com/problems/Virtual-Boolean-Array](https://binarysearch.com/problems/Virtual-Boolean-Array){:target="\_blank"}

## Examples

### Example 1

**Input**

- methods = `['constructor', 'getValue', 'setAllTrue', 'getValue', 'setFalse', 'getValue']`
- arguments = `[[], [9], [], [3], [4], [4]]`

**Output**

- answer = `[None, False, None, True, None, False]`

**Explanation**

```
a = BooleanArray()
a.getValue(9) == False
a.setAllTrue()
a.getValue(3) == True
a.setFalse(4)
a.getValue(4) == False
```

### Example 2

**Input**

- methods = `['constructor', 'setTrue', 'getValue', 'setFalse', 'getValue']`
- arguments = `[[], [5], [5], [5], [5]]`

**Output**

- answer = `[None, None, True, None, False]`

**Explanation**

```
a = BooleanArray()
a.setTrue(5)
a.getValue(5) == True
a.setFalse(5)
a.getValue(5) == False
```

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Virtual-Boolean-Array.py"></script>
