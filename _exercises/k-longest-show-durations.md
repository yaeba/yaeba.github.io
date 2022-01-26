---
title: "K Longest Show Durations"
---

Given a list of strings `shows`, a list of integers `durations`, and an integer `k`, where `shows[i]` and `durations[i]` represent the name and duration watched by the `i`th person, return the total duration watched of the `k` most watched shows.

**Constraints**

- `0 ≤ k ≤ n ≤ 100,000` where `n` is the length of `shows` and `durations`

[https://binarysearch.com/problems/K-Longest-Show-Durations](https://binarysearch.com/problems/K-Longest-Show-Durations){:target="\_blank"}

## Examples

### Example 1

**Input**

- shows = `['Top Gun', 'Aviator', 'Top Gun', 'Roma', 'Logan']`
- durations = `[5, 3, 5, 13, 4]`
- k = `2`

**Output**

- answer = `23`

**Explanation**

The top `2` most watched movies are "Roma" and "Top Gun" for total durations of `13` and `10 = 5+ 5`.

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=K-Longest-Show-Durations.py"></script>
