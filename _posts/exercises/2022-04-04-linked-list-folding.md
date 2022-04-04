---
title: "Linked List Folding"
tags: ["linked list"]
---

You are given a singly linked list `node` containing integer values. Take the first half of the linked list and fold over the second half and merge the intersecting nodes by taking their sum.

**Constraints**

- `1 ≤ n ≤ 100,000` where `n` is the number of nodes in `node`

[https://binarysearch.com/problems/Linked-List-Folding](https://binarysearch.com/problems/Linked-List-Folding){:target="\_blank"}

<script src="/assets/js/viz/viz.js"></script>
<script src="/assets/js/viz/lite.render.js"></script>

## Examples

### Example 1

**Input**

- node =

<div id="example1Node" style="text-align: center"></div>
<script>
  var viz = new Viz();
  
  viz.renderSVGElement("digraph example1Node { 0 [label = 2]; 1 [label = 1]; 2 [label = 3]; 0->1->2; rankdir=LR }")
  .then(function(element) {
    document.getElementById("example1Node").appendChild(element);
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
  
  viz.renderSVGElement("digraph example1Output { 0 [label = 1]; 1 [label = 5]; 0->1; rankdir=LR }")
  .then(function(element) {
    document.getElementById("example1Output").appendChild(element);
  })
  .catch(error => {
    viz = new Viz();
    console.error(error);
  });
</script>

**Explanation**

We fold at the `1`, which doesn't change, and `2` and `3` get merged into `5`.

### Example 2

**Input**

- node =

<div id="example2Node" style="text-align: center"></div>
<script>
  var viz = new Viz();
  
  viz.renderSVGElement("digraph example2Node { 0 [label = 3]; 1 [label = 1]; 2 [label = 2]; 3 [label = 4]; 0->1->2->3; rankdir=LR }")
  .then(function(element) {
    document.getElementById("example2Node").appendChild(element);
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
  
  viz.renderSVGElement("digraph example2Output { 0 [label = 3]; 1 [label = 7]; 0->1; rankdir=LR }")
  .then(function(element) {
    document.getElementById("example2Output").appendChild(element);
  })
  .catch(error => {
    viz = new Viz();
    console.error(error);
  });
</script>

**Explanation**

We fold the linked list so the `3` and `4` get merged into 7, and the `1` and `2` get merged into `3`.

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Linked-List-Folding.cpp"></script>
