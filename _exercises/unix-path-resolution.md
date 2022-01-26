---
title: "Unix Path Resolution"
tags: ["stack"]
---

Given a Unix `path`, represented as a list of strings, return its resolved version.

In Unix, `".."` means to go to the previous directory and `"."` means to stay on the current directory. By resolving, we mean to evaluate the two symbols so that we get the final directory we're currently in.

**Constraints**

- `n ≤ 100,000` where `n` is the length of `path`

[https://binarysearch.com/problems/Unix-Path-Resolution](https://binarysearch.com/problems/Unix-Path-Resolution){:target="\_blank"}

## Examples

### Example 1

**Input**

- path = `['usr', '..', 'usr', '.', 'local', 'bin', 'docker']`

**Output**

- answer = `['usr', 'local', 'bin', 'docker']`

**Explanation**

The input represents "/usr/../usr/./local/bin" which resolves to "/usr/local/bin/docker"

### Example 2

**Input**

- path = `['bin', '..', '..']`

**Output**

- answer = `[]`

**Explanation**

The input represents "/bin/../.." which resolves to "/"

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Unix-Path-Resolution.cpp"></script>
