---
title: "Interleaved Linked List"
tags: ["linked list"]
---

Given two linked lists `l0` and `l1`, return the two linked lists interleaved, starting with `l0`. If there are leftover nodes in a linked list, they should be added to the end.

**Constraints**

- `n ≤ 100,000` where `n` is the number of nodes in `l0`
- `m ≤ 100,000` where `m` is the number of nodes in `l1`

[https://binarysearch.com/problems/Interleaved-Linked-List](https://binarysearch.com/problems/Interleaved-Linked-List){:target="\_blank"}

<script src="/assets/js/viz/viz.js"></script>
<script src="/assets/js/viz/lite.render.js"></script>

## Examples

### Example 1

**Input**

- l0 =

<div id="example1L0" style="text-align: center"></div>
<script>
  var viz = new Viz();
  
  viz.renderSVGElement("digraph example1L0 { 0 [label = 7]; 1 [label = 8]; 0->1; rankdir=LR }")
  .then(function(element) {
    document.getElementById("example1L0").appendChild(element);
  })
  .catch(error => {
    viz = new Viz();
    console.error(error);
  });
</script>

- l1 =

<div id="example1L1" style="text-align: center"></div>
<script>
  var viz = new Viz();
  
  viz.renderSVGElement("digraph example1L1 { 0 [label = 1]; 1 [label = 2]; 0->1; rankdir=LR }")
  .then(function(element) {
    document.getElementById("example1L1").appendChild(element);
  })
  .catch(error => {
    viz = new Viz();
    console.error(error);
  });
</script>

**Output**

- answer =

<div id="example1Output" style="text-align: center"></div>
<script>
  var viz = new Viz();
  
  viz.renderSVGElement("digraph example1Output { 0 [label = 7]; 1 [label = 1]; 2 [label = 8]; 3 [label = 2]; 0->1->2->3; rankdir=LR }")
  .then(function(element) {
    document.getElementById("example1Output").appendChild(element);
  })
  .catch(error => {
    viz = new Viz();
    console.error(error);
  });
</script>

### Example 2

**Input**

- l0 =

<div id="example2L0" style="text-align: center"></div>
<script>
  var viz = new Viz();
  
  viz.renderSVGElement("digraph example2L0 { 0 [label = 7]; 1 [label = 8]; 0->1; rankdir=LR }")
  .then(function(element) {
    document.getElementById("example2L0").appendChild(element);
  })
  .catch(error => {
    viz = new Viz();
    console.error(error);
  });
</script>

- l1 =

<div id="example2L1" style="text-align: center"></div>
<script>
  var viz = new Viz();
  
  viz.renderSVGElement("digraph example2L1 { 0 [label = 1]; 0; rankdir=LR }")
  .then(function(element) {
    document.getElementById("example2L1").appendChild(element);
  })
  .catch(error => {
    viz = new Viz();
    console.error(error);
  });
</script>

**Output**

- answer =

<div id="example2Output" style="text-align: center"></div>
<script>
  var viz = new Viz();
  
  viz.renderSVGElement("digraph example2Output { 0 [label = 7]; 1 [label = 1]; 2 [label = 8]; 0->1->2; rankdir=LR }")
  .then(function(element) {
    document.getElementById("example2Output").appendChild(element);
  })
  .catch(error => {
    viz = new Viz();
    console.error(error);
  });
</script>

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Interleaved-Linked-List.cpp"></script>
