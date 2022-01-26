---
title: "Ancient Astronaut Theory"
---

You are given a string `dictionary`, representing a partial lexicographic ordering of ancient astronauts' dictionary. Given a string `s`, return whether it's a lexicographically sorted string according to this ancient astronaut dictionary.

[https://binarysearch.com/problems/Ancient-Astronaut-Theory](https://binarysearch.com/problems/Ancient-Astronaut-Theory){:target="\_blank"}

## Examples

### Example 1

**Input**

- dictionary = `acb`
- s = `aaaacccbc`

**Output**

- answer = `False`

**Explanation**

This is false because of the last `c`, which comes after `b`.

### Example 2

**Input**

- dictionary = `acb`
- s = `aaaa h ccc i bbb`

**Output**

- answer = `True`

**Explanation**

The only constraint is that `a` comes before `c` which comes before `b` .

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Ancient-Astronaut-Theory.py"></script>
