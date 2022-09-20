---
title: "Frequency Stack"
tags: ["hash table", "data structure"]
---

Implement a frequency stack with the following methods:

- `FrequencyStack()` constructs a new instance of a frequency stack
- `append(int val)` appends `val` to the stack
- `pop()` pops and returns the most frequent element in the stack. If there's more than one most frequent element, the one that's closer to the top of the stack should be popped first.

You can assume that for `pop`, the stack is non-empty when they are called.

**Constraints**

- `n ≤ 100,000` where `n` is the number of methods that will be called to `append` and `pop`

[https://binarysearch.com/problems/Frequency-Stack](https://binarysearch.com/problems/Frequency-Stack){:target="\_blank"}

## Examples

### Example 1

**Input**

- methods = `['constructor', 'append', 'append', 'append', 'pop', 'pop', 'pop']`
- arguments = `[[], [1], [1], [2], [], [], []]`

**Output**

- answer = `[None, None, None, None, 1, 2, 1]`

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Frequency-Stack.py"></script>
