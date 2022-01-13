---
title: "First Post"
excerpt: "The beginning of everything"
---

This is the first post.

There really isn't much to show here. To read more about me, check out [about](/about).

Otherwise, here's a random quote for you:

> No quote for you

> <cite>yaeba</cite>

<script>
  let nodes = document.querySelectorAll("blockquote");
  fetch("https://api.quotable.io/random")
    .then(res => res.json())
    .then(res => {
      nodes[0].innerHTML = res.content;
      nodes[1].innerHTML = `<cite>${res.author}</cite>`;
    });
</script>

<div style="text-align: right; font-style: italic">
  powered by <a href="https://github.com/lukePeavey/quotable">quotable</a>
</div>
