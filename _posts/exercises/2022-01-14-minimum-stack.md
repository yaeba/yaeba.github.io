---
title: "Minimum Stack"
tags: ["data structure"]
---

Implement a stack with the following methods:

- `MinimumStack()` constructs a new instance of a minimum stack
- `append(int val)` appends `val` to the stack
- `peek()` retrieves the last element in the stack
- `min()` retrieves the minimum value in the stack
- `pop()` pops and returns the last element in the stack

Each method should be done in $$\mathcal{O}(1)$$ time. You can assume that for `peek`, `min` and `pop`, the stack is non-empty when they are called.

**Constraints**

- `n ≤ 100,000` where `n` is the number of calls to `append`, `peek`, `min`, and `pop`.

[https://binarysearch.com/problems/Minimum-Stack](https://binarysearch.com/problems/Minimum-Stack){:target="\_blank"}

## Examples

### Example 1

**Input**

- methods = `['constructor', 'append', 'append', 'min', 'peek', 'pop', 'pop']`
- arguments = `[[], [1], [2], [], [], [], []]`

**Output**

- answer = `[None, None, None, 1, 2, 2, 1]`

**Explanation**

- We create a `Minimumstack`
- We append `1` to the stack
- We append `2` to the stack
- We get the min value which is `1`
- We get the top value which is `2`
- We pop the top value which is `2`
- We pop the top value which is `1`

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Minimum-Stack.cpp"></script>
