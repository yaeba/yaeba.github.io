---
title: "Replace Linked List on Index"
tags: ["linked list"]
---

You are given two linked lists `a` and `b` as well as integers `lo` and `hi`.

Remove `a`'s nodes from indices (0-indexed) `[lo, hi]` inclusive and insert `b` in this place.

**Constraints**

- `0 ≤ n ≤ 100,000` where `n` is the number of nodes in `a`
- `0 ≤ m ≤ 100,000` where `m` is the number of nodes in `b`

[https://binarysearch.com/problems/Replace-Linked-List-on-Index](https://binarysearch.com/problems/Replace-Linked-List-on-Index){:target="\_blank"}

<script src="/assets/js/viz/viz.js"></script>
<script src="/assets/js/viz/lite.render.js"></script>

## Examples

### Example 1

**Input**

- a =

<div id="example1A" style="text-align: center"></div>
<script>
  var viz = new Viz();
  
  viz.renderSVGElement("digraph example1A { 0 [label = 1]; 1 [label = 2]; 2 [label = 3]; 3 [label = 4]; 4 [label = 5]; 5 [label = 6]; 0->1->2->3->4->5; rankdir=LR }")
  .then(function(element) {
    document.getElementById("example1A").appendChild(element);
  })
  .catch(error => {
    viz = new Viz();
    console.error(error);
  });
</script>

- b =

<div id="example1B" style="text-align: center"></div>
<script>
  var viz = new Viz();
  
  viz.renderSVGElement("digraph example1B { 0 [label = 10]; 1 [label = 20]; 2 [label = 30]; 0->1->2; rankdir=LR }")
  .then(function(element) {
    document.getElementById("example1B").appendChild(element);
  })
  .catch(error => {
    viz = new Viz();
    console.error(error);
  });
</script>

- lo = `1`
- hi = `2`

**Output**

- answer =

<div id="example1Output" style="text-align: center"></div>
<script>
  var viz = new Viz();
  
  viz.renderSVGElement("digraph example1Output { 0 [label = 1]; 1 [label = 10]; 2 [label = 20]; 3 [label = 30]; 4 [label = 4]; 5 [label = 5]; 6 [label = 6]; 0->1->2->3->4->5->6; rankdir=LR }")
  .then(function(element) {
    document.getElementById("example1Output").appendChild(element);
  })
  .catch(error => {
    viz = new Viz();
    console.error(error);
  });
</script>

**Explanation**

We removed nodes `2` and `3` since their indices are in `[1, 2]`. In its place we inserted `b`.

### Example 2

**Input**

- a =

<div id="example2A" style="text-align: center"></div>
<script>
  var viz = new Viz();
  
  viz.renderSVGElement("digraph example2A { 0 [label = 1]; 1 [label = 2]; 2 [label = 3]; 0->1->2; rankdir=LR }")
  .then(function(element) {
    document.getElementById("example2A").appendChild(element);
  })
  .catch(error => {
    viz = new Viz();
    console.error(error);
  });
</script>

- b =

<div id="example2B" style="text-align: center"></div>
<script>
  var viz = new Viz();
  
  viz.renderSVGElement("digraph example2B { 0 [label = 10]; 1 [label = 20]; 2 [label = 30]; 0->1->2; rankdir=LR }")
  .then(function(element) {
    document.getElementById("example2B").appendChild(element);
  })
  .catch(error => {
    viz = new Viz();
    console.error(error);
  });
</script>

- lo = `0`
- hi = `2`

**Output**

- answer =

<div id="example2Output" style="text-align: center"></div>
<script>
  var viz = new Viz();
  
  viz.renderSVGElement("digraph example2Output { 0 [label = 10]; 1 [label = 20]; 2 [label = 30]; 0->1->2; rankdir=LR }")
  .then(function(element) {
    document.getElementById("example2Output").appendChild(element);
  })
  .catch(error => {
    viz = new Viz();
    console.error(error);
  });
</script>

**Explanation**

We removed every node of `a` and inserted `b`.

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Replace-Linked-List-on-Index.cpp"></script>
