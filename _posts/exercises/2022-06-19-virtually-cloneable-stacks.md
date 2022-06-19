---
title: "Virtually Cloneable Stacks"
tags: ["data structure"]
---

Implement a data structure `VirtuallyCloneableStacks` with the following methods

- `VirtuallyCloneableStacks()` which initializes an empty stack at index `0`.
- `copyPush(i)` which clones the stack at index `i`, pushes an element to the clone, and then pushes the clone into the list of stacks.
- `copyPop(i)` which clones the stack at index `i`, pops an element from the clone, and then pushes the clone into the list of stacks.
- `size(i)` which returns the number of elements in stack at index `i`.

You can assume that each call will be valid. For example, a stack won't be popped from an empty stack, and `i` will be in bounds.

**Constraints**

- `0 ≤ n ≤ 100,000` where `n` is the number of method calls.

[https://binarysearch.com/problems/Virtually-Cloneable-Stacks](https://binarysearch.com/problems/Virtually-Cloneable-Stacks){:target="\_blank"}

## Examples

### Example 1

**Input**

- methods = `['constructor', 'copyPush', 'copyPush', 'copyPop', 'size', 'size', 'size', 'size']`
- arguments = `[[], [0], [1], [2], [0], [1], [2], [3]]`

**Output**

- answer = `[None, None, None, None, 0, 1, 2, 1]`

**Explanation**

```
s = VirtuallyCloneableStacks()
s.copyPush(0)
s.copyPush(1)
s.copyPop(2)
s.size(0) == 0
s.size(1) == 1
s.size(2) == 2
s.size(3) == 1
```

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Virtually-Cloneable-Stacks.py"></script>
