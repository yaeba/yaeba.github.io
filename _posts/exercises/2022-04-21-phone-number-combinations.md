---
title: "Phone Number Combinations"
tags: ["recursion", "backtracking"]
---

Given a string `digits` containing `2` to `9` inclusive, return in sorted lexicographic order all possible strings it could represent when mapping to letters on a phone dialpad.

These are the mappings on a phone dialpad:

```
| 2 | abc  |
| 3 | def  |
| 4 | ghi  |
| 5 | jkl  |
| 6 | mno  |
| 7 | pqrs |
| 8 | tuv  |
| 9 | wxyz |
```

[https://binarysearch.com/problems/Phone-Number-Combinations](https://binarysearch.com/problems/Phone-Number-Combinations){:target="\_blank"}



## Examples
### Example 1

**Input**

- digits = `23`

**Output**

- answer = `['ad', 'ae', 'af', 'bd', 'be', 'bf', 'cd', 'ce', 'cf']`




## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Phone-Number-Combinations.py"></script>

```
