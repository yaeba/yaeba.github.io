---
title: "Linked List Union"
tags: ["linked list"]
---

Given two sorted linked lists `node0`, and `node`, return a new sorted linked list containing the union of the two lists.

**Constraints**

- `0 ≤ n ≤ 100,000` where `n` is the number of nodes in `node0`
- `0 ≤ m ≤ 100,000` where `m` is the number of nodes in `node1`

[https://binarysearch.com/problems/Linked-List-Union](https://binarysearch.com/problems/Linked-List-Union){:target="\_blank"}

<script src="/assets/js/viz/viz.js"></script>
<script src="/assets/js/viz/lite.render.js"></script>

## Examples

### Example 1

**Input**

- ll0 =

<div id="example1Ll0" style="text-align: center"></div>
<script>
  var viz = new Viz();
  
  viz.renderSVGElement("digraph example1Ll0 { 0 [label = 1]; 1 [label = 3]; 2 [label = 4]; 0->1->2; rankdir=LR }")
  .then(function(element) {
    document.getElementById("example1Ll0").appendChild(element);
  })
  .catch(error => {
    viz = new Viz();
    console.error(error);
  });
</script>

- ll1 =

<div id="example1Ll1" style="text-align: center"></div>
<script>
  var viz = new Viz();
  
  viz.renderSVGElement("digraph example1Ll1 { 0 [label = 2]; 1 [label = 3]; 2 [label = 4]; 0->1->2; rankdir=LR }")
  .then(function(element) {
    document.getElementById("example1Ll1").appendChild(element);
  })
  .catch(error => {
    viz = new Viz();
    console.error(error);
  });
</script>

**Output**

- answer =

<div id="output" style="text-align: center"></div>
<script>
  var viz = new Viz();
  
  viz.renderSVGElement("digraph output { 0 [label = 1]; 1 [label = 2]; 2 [label = 3]; 3 [label = 4]; 0->1->2->3; rankdir=LR }")
  .then(function(element) {
    document.getElementById("output").appendChild(element);
  })
  .catch(error => {
    viz = new Viz();
    console.error(error);
  });
</script>

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Linked-List-Union.cpp"></script>
