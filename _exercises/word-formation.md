---
title: "Word Formation"
tags: ["hash table", "string"]
---

Given a list of strings `words` and a string `letters`, return the length of longest string in `words` that can be made from letters in `letters`. If no word can be made, return `0`.

Note that you can't reuse letters.

**Constraints**

- `n ≤ 10,000` where `n` is the length of `words`
- `m ≤ 1,000` where `m` is the length of `letters`

[https://binarysearch.com/problems/Word-Formation](https://binarysearch.com/problems/Word-Formation){:target="\_blank"}

## Examples

### Example 1

**Input**

- words = `['the', 'word', 'love', 'scott', 'finder', 'dictionary']`
- letters = `fanierdow`

**Output**

- answer = `6`

**Explanation**

We can make the word `finder` out of our letters, which has the longest length of 6.

### Example 2

**Input**

- words = `['credit', 'nirvana', 'karma', 'empathy', 'hang', 'aaaaaaaaa']`
- letters = `afnvlfkm`

**Output**

- answer = `0`

**Explanation**

We can't make any of these words with the letters we have.

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Word-Formation.py"></script>
