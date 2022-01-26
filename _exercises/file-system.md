---
title: "File System"
tags: ["hash table", "data structure"]
---

Implement a data structure with the following methods:

- `bool create(String path, int content)` which creates a path at `path` if there's a parent directory and `path` doesn't exist yet, and sets its value as `content`. Returns whether it was newly created. Initially only the root directory at `"/"` exists.
- `int get(String path)` which returns the value associated with `path`. If there's no path, return `-1`.

**Constraints**

- `0 ≤ n ≤ 100,000` where `n` is the number of calls to `create` and `get`

[https://binarysearch.com/problems/File-System](https://binarysearch.com/problems/File-System){:target="\_blank"}

## Examples

### Example 1

**Input**

- methods = `['constructor', 'create', 'create', 'get', 'get', 'create', 'get']`
- arguments = `[[], ['/usr', 1], ['/usr/bin', 2], ['/usr'], ['/usr/bin'], ['/proc/1/exe', 3], ['/non/existent']]`

**Output**

- answer = `[None, True, True, 1, 2, False, -1]`

**Explanation**

```
fs = FileSystem() # Only "/" exists
fs.create("/usr", 1) == True # Now "/" and "/usr" exists
fs.create("/usr/bin", 2) == True# Now "/", "/usr" and "/usr/bin" exists
fs.get("/usr") == 1
fs.get("/usr/bin") == 2
fs.create("/proc/1/exe", 3) == False # Parent dir "/proc/1/" doesn't exist, so can't create here
fs.get("/non/existent") == -1
```

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=File-System.py"></script>
