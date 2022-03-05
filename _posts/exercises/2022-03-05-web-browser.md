---
title: "Web Browser"
tags: ["data structure"]
---

Implement a web browser with the following methods:

- `WebBrowser(String homepage)` constructs a new instance of the browser with starting page of `homepage`.
- `visit(String page)` visits the site `page`, clearing all forward history.
- `back(int n)` goes back `n` number of steps in history and returns the current page. Note that once you reach the `homepage`, you stay on that page even if you go `back`.
- `forward(int n)` goes forward `n` number of steps in history and returns the current page. Note that once you reach the most recent page, you stay on that page even if you go `forward`.

**Constraints**

- `n ≤ 100,000` where `n` is the number of calls to `visit`, `back` and `forward`.

[https://binarysearch.com/problems/Web-Browser](https://binarysearch.com/problems/Web-Browser){:target="\_blank"}

## Examples

### Example 1

**Input**

- methods = `['constructor', 'visit', 'visit', 'visit', 'back', 'forward']`
- arguments = `[['wikipedia.org'], ['google.com'], ['stackoverflow.com'], ['github.com'], [2], [1]]`

**Output**

- answer = `[None, None, None, None, 'google.com', 'stackoverflow.com']`

**Explanation**

```
browser = WebBrowser("wikipedia.org")
browser.visit("google.com")
browser.visit("stackoverflow.com")
browser.visit("github.com")
browser.back(2) == "google.com"
browser.forward(1) == "stackoverflow.com"
```

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Web-Browser.cpp"></script>
