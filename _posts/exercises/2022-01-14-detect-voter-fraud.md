---
title: "Detect Voter Fraud"
tags: ["hash table"]
---

Given a two dimensional list of integers `votes`, where each list has two elements `[candidate_id, voter_id]`, report whether any voter has voted more than once.

**Constraints**

- `n ≤ 100,000` where `n` is the length of `votes`

[https://binarysearch.com/problems/Detect-Voter-Fraud](https://binarysearch.com/problems/Detect-Voter-Fraud){:target="\_blank"}

## Examples

### Example 1

**Input**

- votes =

```
[[3,1],
 [3,0],
 [3,4],
 [3,3],
 [3,2]]
```

**Output**

- answer = `False`

**Explanation**

Every voter has voted once.

### Example 2

**Input**

- votes =

```
[[2,3],
 [2,2],
 [2,1],
 [2,0],
 [2,1]]
```

**Output**

- answer = `True`

**Explanation**

The voter with voter_id `1` voted twice.

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Detect-Voter-Fraud.java"></script>
