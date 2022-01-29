---
title: "Rotate Linked List by K"
tags: ["two pointers", "linked list"]
---

Given a linked list `node` and a non-negative integer `k`, rotate the list to the right by `k` places.

Note: The linked list is guaranteed to have at least one element, and k is guaranteed to be less than or equal to the length of the list.

**Constraints**

- `k ≤ n ≤ 100,000` where `n` is the number of nodes in `node`

[https://binarysearch.com/problems/Rotate-Linked-List-by-K](https://binarysearch.com/problems/Rotate-Linked-List-by-K){:target="\_blank"}

<script src="/assets/js/viz/viz.js"></script>
<script src="/assets/js/viz/lite.render.js"></script>

## Examples

### Example 1

**Input**

- node =

<div id="example1Node" style="text-align: center"></div>
<script>
  var viz = new Viz();
  
  viz.renderSVGElement("digraph example1Node { 0 [label = 1]; 1 [label = 2]; 2 [label = 3]; 3 [label = 4]; 0->1->2->3; rankdir=LR }")
  .then(function(element) {
    document.getElementById("example1Node").appendChild(element);
  })
  .catch(error => {
    viz = new Viz();
    console.error(error);
  });
</script>

- k = `4`

**Output**

- answer =

<div id="example1Output" style="text-align: center"></div>
<script>
  var viz = new Viz();
  
  viz.renderSVGElement("digraph example1Output { 0 [label = 1]; 1 [label = 2]; 2 [label = 3]; 3 [label = 4]; 0->1->2->3; rankdir=LR }")
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
  
  viz.renderSVGElement("digraph example2Node { 0 [label = 1]; 1 [label = 2]; 2 [label = 3]; 3 [label = 4]; 0->1->2->3; rankdir=LR }")
  .then(function(element) {
    document.getElementById("example2Node").appendChild(element);
  })
  .catch(error => {
    viz = new Viz();
    console.error(error);
  });
</script>

- k = `0`

**Output**

- answer =

<div id="example2Output" style="text-align: center"></div>
<script>
  var viz = new Viz();
  
  viz.renderSVGElement("digraph example2Output { 0 [label = 1]; 1 [label = 2]; 2 [label = 3]; 3 [label = 4]; 0->1->2->3; rankdir=LR }")
  .then(function(element) {
    document.getElementById("example2Output").appendChild(element);
  })
  .catch(error => {
    viz = new Viz();
    console.error(error);
  });
</script>

### Example 3

**Input**

- node =

<div id="example3Node" style="text-align: center"></div>
<script>
  var viz = new Viz();
  
  viz.renderSVGElement("digraph example3Node { 0 [label = 1]; 1 [label = 2]; 2 [label = 3]; 3 [label = 4]; 0->1->2->3; rankdir=LR }")
  .then(function(element) {
    document.getElementById("example3Node").appendChild(element);
  })
  .catch(error => {
    viz = new Viz();
    console.error(error);
  });
</script>

- k = `2`

**Output**

- answer =

<div id="example3Output" style="text-align: center"></div>
<script>
  var viz = new Viz();
  
  viz.renderSVGElement("digraph example3Output { 0 [label = 3]; 1 [label = 4]; 2 [label = 1]; 3 [label = 2]; 0->1->2->3; rankdir=LR }")
  .then(function(element) {
    document.getElementById("example3Output").appendChild(element);
  })
  .catch(error => {
    viz = new Viz();
    console.error(error);
  });
</script>

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Rotate-Linked-List-by-K.cpp"></script>
