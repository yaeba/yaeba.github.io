---
title: "Linked List Delete Last Occurrence of Value"
tags: ["linked list"]
---

Given a singly linked list `node`, and an integer `target`, delete the last occurrence of `target` in `node`.

**Constraints**

- `0 ≤ n ≤ 100,000` where `n` is the number of nodes in `node`

[https://binarysearch.com/problems/Linked-List-Delete-Last-Occurrence-of-Value](https://binarysearch.com/problems/Linked-List-Delete-Last-Occurrence-of-Value){:target="\_blank"}

<script src="/assets/js/viz/viz.js"></script>
<script src="/assets/js/viz/lite.render.js"></script>

## Examples

### Example 1

**Input**

- node =

<div id="example1Node" style="text-align: center"></div>
<script>
  var viz = new Viz();
  
  viz.renderSVGElement("digraph example1Node { 0 [label = 1]; 1 [label = 2]; 2 [label = 3]; 3 [label = 1]; 0->1->2->3; rankdir=LR }")
  .then(function(element) {
    document.getElementById("example1Node").appendChild(element);
  })
  .catch(error => {
    viz = new Viz();
    console.error(error);
  });
</script>

- target = `1`

**Output**

- answer =

<div id="example1Output" style="text-align: center"></div>
<script>
  var viz = new Viz();
  
  viz.renderSVGElement("digraph example1Output { 0 [label = 1]; 1 [label = 2]; 2 [label = 3]; 0->1->2; rankdir=LR }")
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

- node =

<div id="example2Node" style="text-align: center"></div>
<script>
  var viz = new Viz();
  
  viz.renderSVGElement("digraph example2Node { 0 [label = 1]; 1 [label = 2]; 2 [label = 3]; 3 [label = 1]; 0->1->2->3; rankdir=LR }")
  .then(function(element) {
    document.getElementById("example2Node").appendChild(element);
  })
  .catch(error => {
    viz = new Viz();
    console.error(error);
  });
</script>

- target = `3`

**Output**

- answer =

<div id="example2Output" style="text-align: center"></div>
<script>
  var viz = new Viz();
  
  viz.renderSVGElement("digraph example2Output { 0 [label = 1]; 1 [label = 2]; 2 [label = 1]; 0->1->2; rankdir=LR }")
  .then(function(element) {
    document.getElementById("example2Output").appendChild(element);
  })
  .catch(error => {
    viz = new Viz();
    console.error(error);
  });
</script>

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Linked-List-Delete-Last-Occurrence-of-Value.cpp"></script>
