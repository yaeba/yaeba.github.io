---
title: "Text Editor"
tags: ["stack"]
---

Given a string `s` representing characters typed into an editor, with `"<-"` representing a backspace, return the current state of the editor.

**Constraints**

- `n ≤ 100,000` where `n` is the length of `s`

[https://binarysearch.com/problems/Text-Editor](https://binarysearch.com/problems/Text-Editor){:target="\_blank"}

## Examples

### Example 1

**Input**

- s = `abc<-z`

**Output**

- answer = `abz`

**Explanation**

The "c" got deleted by the backspace.

### Example 2

**Input**

- s = `<-x<-z<-`

**Output**

- answer = ``

**Explanation**

All characters are deleted. Also note you can type backspace when the editor is empty as well.

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Text-Editor.cpp"></script>
