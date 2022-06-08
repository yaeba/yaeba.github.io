---
title: "Flight Itinerary"
tags: ["graph"]
---

You are given a list of flights that were taken, represented as origin to destination airport pairs. Given that this list was shuffled, find all the airports that were visited in the correct order.

Note: you can assume that no airport was visited twice.

**Constraints**

- `n ≤ 100,000` where n is the length of `flights`

[https://binarysearch.com/problems/Flight-Itinerary](https://binarysearch.com/problems/Flight-Itinerary){:target="\_blank"}

## Examples

### Example 1

**Input**

- flights =

```
[['WRE','RPM'],
 ['AGN','WRE'],
 ['NTL','AGN']]
```

**Output**

- answer = `['NTL', 'AGN', 'WRE', 'RPM']`

**Explanation**

The only way to have taken the 3 flights was to have taken "NTL" -> "AGN" first. After that, "AGN" -> "WRE", and "WRE" -> "RPM" could be taken.

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Flight-Itinerary.py"></script>
