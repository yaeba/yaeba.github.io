---
title: "Airplane Seat Shuffling"
tags: ["dynamic programming", "math"]
---

You are given an integer `n` representing the number of seats in an airplane. The first person has lost their ticket, so they pick a random seat. Everyone else still has their ticket, but if their seat is already taken, they will also randomly pick an available seat.

Return the probability that the last person gets their assigned seat.

**Constraints**

- `n ≤ 100,000`

[https://binarysearch.com/problems/Airplane-Seat-Shuffling](https://binarysearch.com/problems/Airplane-Seat-Shuffling){:target="\_blank"}

## Examples

### Example 1

**Input**

- n = `2`

**Output**

- answer = `0.5`

**Explanation**

There's two choices here. Either the first person takes the second person's seat or they don't. Each has 50% chance.

### Example 2

**Input**

- n = `1`

**Output**

- answer = `1`

**Explanation**

They can only take their own seat.

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Airplane-Seat-Shuffling.cpp"></script>
