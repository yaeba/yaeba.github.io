---
title: "Revolving Door"
---

You are given a list of list of integers `requests`. `requests[i]` contains `[time, direction]` meaning at time `time`, a person arrived at the door and either wanted to go in (`1`) or go out (`0`).

Given that there's only one door and it takes one time unit to use the door, we have the following rules to resolve conflicts:

- The door starts with `in` position and then is set to the position used by the last person.
- If there's only one person at the door at given time, they can use the door.
- When two or more people want to go in, earliest person goes first and then the direction previously used holds precedence.
- If no one uses the door for one time unit, it reverts back to the starting `in` position.

Return a sorted list of lists where each element contains `[time, direction]`, meaning at `time`, a person either went in or out.

**Constraints**

- `0 ≤ n ≤ 100,000` where `n` is the length of `requests`

[https://binarysearch.com/problems/Revolving-Door](https://binarysearch.com/problems/Revolving-Door){:target="\_blank"}

## Examples

### Example 1

**Input**

- requests = `[[1, 0], [2, 1], [5, 0], [5, 1], [2, 0]]`

**Output**

- answer = `[[1, 0], [2, 0], [3, 1], [5, 1], [6, 0]]`

**Explanation**

The door starts as `in`

- At time `1`, there's only one person so they can go out. Door becomes out.
- At time `2`, there's two people but the person going out has priority so they go out.
- At time `3`, the person looking to go in can now go in.
- At time `5`, there's two people but the person going in has priority so they go out.
- At time `6`, the last person can go out.

### Example 2

**Input**

- requests = `[[1, 0], [2, 0], [2, 1], [1, 1]]`

**Output**

- answer = `[[1, 1], [2, 0], [3, 0], [4, 1]]`

**Explanation**

The door starts as `in`

- At time `1`, there's two people but the person going in has higher priority.
- At time `2`, the other person who came at time `1` can go out. Door becomes `out`
- At time `3`, there's two people but the person going out has higher priority.
- At time `4`, the last person can go in

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Revolving-Door.py"></script>
