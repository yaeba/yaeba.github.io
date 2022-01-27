---
title: "Next Node on Its Right"
tags: ["tree"]
---

You are given a binary tree `root` containing unique values, and an integer `target`. Find the node with value `target` and return the node that's directly right of it on its level. If the target node doesn't exist or if it's already in the rightmost position, return null.

**Constraints**

- `0 ≤ n ≤ 100,000` where `n` is the number of nodes in `root`

[https://binarysearch.com/problems/Next-Node-on-Its-Right](https://binarysearch.com/problems/Next-Node-on-Its-Right){:target="\_blank"}

<script src="/assets/js/viz/viz.js"></script>
<script src="/assets/js/viz/lite.render.js"></script>

## Examples

### Example 1

**Input**

- tree =

<div id="example1Tree" style="text-align: center"></div>
<script>
  var viz = new Viz();
  
  viz.renderSVGElement("digraph example1Tree { 0 [label = 1]; C0 [style = invis, width = 0, label = \"\"]; 1 [label = 2]; C1 [style = invis, width = 0, label = \"\"]; 2 [label = 3]; C2 [style = invis, width = 0, label = \"\"]; 3 [label = 4]; C3 [style = invis, width = 0, label = \"\"]; 4 [label = 5]; C4 [style = invis, width = 0, label = \"\"]; 5 [label = 6]; C5 [style = invis, width = 0, label = \"\"]; 6 [label = 7]; C6 [style = invis, width = 0, label = \"\"]; 0 -> 1; 0 -> C0 [style = invis]; 0 -> 2; {rank = same; 1 -> C0 -> 2 [style = invis]}; 1 -> 3; 1 -> C1 [style = invis]; 1 -> 4; {rank = same; 3 -> C1 -> 4 [style = invis]}; 2 -> L2 [style = invis]; 2 -> C2 [style = invis]; 2 -> 5; {rank = same; L2 -> C2 -> 5 [style = invis]}; L2 [style = invis, width = 0, label = \"\"]; 3 -> L3 [style = invis]; 3 -> C3 [style = invis]; 3 -> R3 [style = invis]; {rank = same; L3 -> C3 -> R3 [style = invis]}; L3 [style = invis, width = 0, label = \"\"]; R3 [style = invis, width = 0, label = \"\"]; 4 -> L4 [style = invis]; 4 -> C4 [style = invis]; 4 -> R4 [style = invis]; {rank = same; L4 -> C4 -> R4 [style = invis]}; L4 [style = invis, width = 0, label = \"\"]; R4 [style = invis, width = 0, label = \"\"]; 5 -> 6; 5 -> C5 [style = invis]; 5 -> R5 [style = invis]; {rank = same; 6 -> C5 -> R5 [style = invis]}; R5 [style = invis, width = 0, label = \"\"]; 6 -> L6 [style = invis]; 6 -> C6 [style = invis]; 6 -> R6 [style = invis]; {rank = same; L6 -> C6 -> R6 [style = invis]}; L6 [style = invis, width = 0, label = \"\"]; R6 [style = invis, width = 0, label = \"\"] }")
  .then(function(element) {
    document.getElementById("example1Tree").appendChild(element);
  })
  .catch(error => {
    viz = new Viz();
    console.error(error);
  });
</script>

- target = `5`

**Output**

- answer =

<div id="output" style="text-align: center"></div>
<script>
  var viz = new Viz();
  
  viz.renderSVGElement("digraph output { 0 [label = 6]; C0 [style = invis, width = 0, label = \"\"]; 1 [label = 7]; C1 [style = invis, width = 0, label = \"\"]; 0 -> 1; 0 -> C0 [style = invis]; 0 -> R0 [style = invis]; {rank = same; 1 -> C0 -> R0 [style = invis]}; R0 [style = invis, width = 0, label = \"\"]; 1 -> L1 [style = invis]; 1 -> C1 [style = invis]; 1 -> R1 [style = invis]; {rank = same; L1 -> C1 -> R1 [style = invis]}; L1 [style = invis, width = 0, label = \"\"]; R1 [style = invis, width = 0, label = \"\"] }")
  .then(function(element) {
    document.getElementById("output").appendChild(element);
  })
  .catch(error => {
    viz = new Viz();
    console.error(error);
  });
</script>

**Explanation**

### Example 2

**Input**

- tree =

<div id="example2Tree" style="text-align: center"></div>
<script>
  var viz = new Viz();
  
  viz.renderSVGElement("digraph example2Tree { 0 [label = 1]; C0 [style = invis, width = 0, label = \"\"]; 1 [label = 2]; C1 [style = invis, width = 0, label = \"\"]; 2 [label = 3]; C2 [style = invis, width = 0, label = \"\"]; 0 -> 1; 0 -> C0 [style = invis]; 0 -> 2; {rank = same; 1 -> C0 -> 2 [style = invis]}; 1 -> L1 [style = invis]; 1 -> C1 [style = invis]; 1 -> R1 [style = invis]; {rank = same; L1 -> C1 -> R1 [style = invis]}; L1 [style = invis, width = 0, label = \"\"]; R1 [style = invis, width = 0, label = \"\"]; 2 -> L2 [style = invis]; 2 -> C2 [style = invis]; 2 -> R2 [style = invis]; {rank = same; L2 -> C2 -> R2 [style = invis]}; L2 [style = invis, width = 0, label = \"\"]; R2 [style = invis, width = 0, label = \"\"] }")
  .then(function(element) {
    document.getElementById("example2Tree").appendChild(element);
  })
  .catch(error => {
    viz = new Viz();
    console.error(error);
  });
</script>

- target = `3`

**Output**

- answer =

<div id="output" style="text-align: center"></div>
<script>
  var viz = new Viz();
  
  viz.renderSVGElement("digraph output {  }")
  .then(function(element) {
    document.getElementById("output").appendChild(element);
  })
  .catch(error => {
    viz = new Viz();
    console.error(error);
  });
</script>

**Explanation**

There's no node directly to the right of `3`.

### Example 3

**Input**

- tree =

<div id="example3Tree" style="text-align: center"></div>
<script>
  var viz = new Viz();
  
  viz.renderSVGElement("digraph example3Tree { 0 [label = 1]; C0 [style = invis, width = 0, label = \"\"]; 0 -> L0 [style = invis]; 0 -> C0 [style = invis]; 0 -> R0 [style = invis]; {rank = same; L0 -> C0 -> R0 [style = invis]}; L0 [style = invis, width = 0, label = \"\"]; R0 [style = invis, width = 0, label = \"\"] }")
  .then(function(element) {
    document.getElementById("example3Tree").appendChild(element);
  })
  .catch(error => {
    viz = new Viz();
    console.error(error);
  });
</script>

- target = `2`

**Output**

- answer =

<div id="output" style="text-align: center"></div>
<script>
  var viz = new Viz();
  
  viz.renderSVGElement("digraph output {  }")
  .then(function(element) {
    document.getElementById("output").appendChild(element);
  })
  .catch(error => {
    viz = new Viz();
    console.error(error);
  });
</script>

**Explanation**

Node `2` doesn't exist.

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Next-Node-on-Its-Right.cpp"></script>
