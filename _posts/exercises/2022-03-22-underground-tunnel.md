---
title: "Underground Tunnel"
tags: ["hash table", "data structure"]
---

Implement a data structure with the following methods:

- `void checkIn(int userId, String station, int timestamp)` which means user `userId` checked in to station `station` at time `timestamp`. A user can only be checked in at one station at a time.
- `void checkOut(int userId, String station, int timestamp)` which means user `userId` checked out of station `station` at time `timestamp`.
- `float averageTime(String start, String end)` returns the average time for a person to move between station `start` and `end`.

You can assume that for a given user, `checkIn` always occurs before `checkOut`. Also, `averageTime` will only be called if at least one person travelled between the two stations.

**Constraints**

- `0 ≤ n ≤ 100,000` where `n` is the number of calls to `checkIn`, `checkOut` and `averageTime`.

[https://binarysearch.com/problems/Underground-Tunnel](https://binarysearch.com/problems/Underground-Tunnel){:target="\_blank"}

## Examples

### Example 1

**Input**

- methods = `['constructor', 'checkIn', 'checkIn', 'checkOut', 'checkOut', 'averageTime']`
- arguments = `[[], [1, 'NYC', 5], [2, 'NYC', 7], [2, 'SFO', 8], [1, 'SFO', 10], ['NYC', 'SFO']]`

**Output**

- answer = `[None, None, None, None, None, 3]`

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Underground-Tunnel.py"></script>
