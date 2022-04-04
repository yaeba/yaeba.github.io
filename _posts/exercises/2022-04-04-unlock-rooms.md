---
title: "Unlock Rooms"
---

You are given a two-dimensional list of integers `rooms`. Each index `i` in `rooms` represents a room and `rooms[i]` represents different keys to unlock other rooms.

You are currently in an unlocked room `0` and every other room is locked. Given you can move freely between unlocked rooms, return whether you can unlock every room.

**Constraints**

- `n, m ≤ 250` where `n` and `m` are the number of rows and columns in `rooms`.

[https://binarysearch.com/problems/Unlock-Rooms](https://binarysearch.com/problems/Unlock-Rooms){:target="\_blank"}

## Examples

### Example 1

**Input**

- rooms = `[[1, 3], [2], [0], []]`

**Output**

- answer = `True`

**Explanation**

We start off at room `0` and can go to room `1` with its key. From room `1` we can go to room `2`. Then, we can go back to room `0` and go to room `3`.

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Unlock-Rooms.py"></script>
