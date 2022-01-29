---
title: "Sorting Mail"
tags: ["bfs"]
---

You are given a list of strings `mailboxes`. Each mailbox is a list of strings, where each string is either `"junk"`, `"personal"`, `"work"`. Go through each mailbox in round robin order starting from the first one, filtering out junk, to form a single pile and return the pile.

**Constraints**

- `0 ≤ n ≤ 100,000` where `n` is the number of elements in `mailboxes`

[https://binarysearch.com/problems/Sorting-Mail](https://binarysearch.com/problems/Sorting-Mail){:target="\_blank"}

## Examples

### Example 1

**Input**

- mailboxes = `[['work', 'personal'], ['junk', 'personal', 'junk'], ['work']]`

**Output**

- answer = `['work', 'work', 'personal', 'personal']`

**Explanation**

In order and without filtering, we'd have `work` -> `junk` -> `work` -> `personal` -> `personal` -> `junk`, and since we filter out junk we get `work` -> `work` -> `personal` -> `personal`.

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Sorting-Mail.py"></script>
