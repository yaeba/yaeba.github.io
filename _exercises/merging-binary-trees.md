---
title: "Merging Binary Trees"
tags: ["tree"]
---

Given two binary trees `node0` and `node1`, return a merge of the two trees where each value is equal to the sum of the values of the corresponding nodes of the input trees. If only one input tree has a node in a given position, the corresponding node in the new tree should match that input node.

**Constraints**

- `n ≤ 100,000` where `n` is the number of nodes in `node0`
- `m ≤ 100,000` where `m` is the number of nodes in `node1`

[https://binarysearch.com/problems/Merging-Binary-Trees](https://binarysearch.com/problems/Merging-Binary-Trees){:target="\_blank"}

<script src="/assets/js/viz/viz.js"></script>
<script src="/assets/js/viz/lite.render.js"></script>

## Examples

### Example 1

**Input**

- node0 =

<div id="example1Node0" style="text-align: center"></div>
<script>
  var viz = new Viz();
  
  viz.renderSVGElement("digraph example1Node0 { 0 [label = 0]; C0 [style = invis, width = 0, label = \"\"]; 1 [label = 3]; C1 [style = invis, width = 0, label = \"\"]; 2 [label = 2]; C2 [style = invis, width = 0, label = \"\"]; 3 [label = 3]; C3 [style = invis, width = 0, label = \"\"]; 0 -> 1; 0 -> C0 [style = invis]; 0 -> 2; {rank = same; 1 -> C0 -> 2 [style = invis]}; 1 -> L1 [style = invis]; 1 -> C1 [style = invis]; 1 -> R1 [style = invis]; {rank = same; L1 -> C1 -> R1 [style = invis]}; L1 [style = invis, width = 0, label = \"\"]; R1 [style = invis, width = 0, label = \"\"]; 2 -> 3; 2 -> C2 [style = invis]; 2 -> R2 [style = invis]; {rank = same; 3 -> C2 -> R2 [style = invis]}; R2 [style = invis, width = 0, label = \"\"]; 3 -> L3 [style = invis]; 3 -> C3 [style = invis]; 3 -> R3 [style = invis]; {rank = same; L3 -> C3 -> R3 [style = invis]}; L3 [style = invis, width = 0, label = \"\"]; R3 [style = invis, width = 0, label = \"\"] }")
  .then(function(element) {
    document.getElementById("example1Node0").appendChild(element);
  })
  .catch(error => {
    viz = new Viz();
    console.error(error);
  });
</script>

- node1 =

<div id="example1Node1" style="text-align: center"></div>
<script>
  var viz = new Viz();
  
  viz.renderSVGElement("digraph example1Node1 { 0 [label = 7]; C0 [style = invis, width = 0, label = \"\"]; 1 [label = 5]; C1 [style = invis, width = 0, label = \"\"]; 2 [label = 1]; C2 [style = invis, width = 0, label = \"\"]; 0 -> 1; 0 -> C0 [style = invis]; 0 -> 2; {rank = same; 1 -> C0 -> 2 [style = invis]}; 1 -> L1 [style = invis]; 1 -> C1 [style = invis]; 1 -> R1 [style = invis]; {rank = same; L1 -> C1 -> R1 [style = invis]}; L1 [style = invis, width = 0, label = \"\"]; R1 [style = invis, width = 0, label = \"\"]; 2 -> L2 [style = invis]; 2 -> C2 [style = invis]; 2 -> R2 [style = invis]; {rank = same; L2 -> C2 -> R2 [style = invis]}; L2 [style = invis, width = 0, label = \"\"]; R2 [style = invis, width = 0, label = \"\"] }")
  .then(function(element) {
    document.getElementById("example1Node1").appendChild(element);
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
  
  viz.renderSVGElement("digraph output { 0 [label = 7]; C0 [style = invis, width = 0, label = \"\"]; 1 [label = 8]; C1 [style = invis, width = 0, label = \"\"]; 2 [label = 3]; C2 [style = invis, width = 0, label = \"\"]; 3 [label = 3]; C3 [style = invis, width = 0, label = \"\"]; 0 -> 1; 0 -> C0 [style = invis]; 0 -> 2; {rank = same; 1 -> C0 -> 2 [style = invis]}; 1 -> L1 [style = invis]; 1 -> C1 [style = invis]; 1 -> R1 [style = invis]; {rank = same; L1 -> C1 -> R1 [style = invis]}; L1 [style = invis, width = 0, label = \"\"]; R1 [style = invis, width = 0, label = \"\"]; 2 -> 3; 2 -> C2 [style = invis]; 2 -> R2 [style = invis]; {rank = same; 3 -> C2 -> R2 [style = invis]}; R2 [style = invis, width = 0, label = \"\"]; 3 -> L3 [style = invis]; 3 -> C3 [style = invis]; 3 -> R3 [style = invis]; {rank = same; L3 -> C3 -> R3 [style = invis]}; L3 [style = invis, width = 0, label = \"\"]; R3 [style = invis, width = 0, label = \"\"] }")
  .then(function(element) {
    document.getElementById("output").appendChild(element);
  })
  .catch(error => {
    viz = new Viz();
    console.error(error);
  });
</script>

### Example 2

**Input**

- node0 =

<div id="example2Node0" style="text-align: center"></div>
<script>
  var viz = new Viz();
  
  viz.renderSVGElement("digraph example2Node0 { 0 [label = 1]; C0 [style = invis, width = 0, label = \"\"]; 1 [label = 2]; C1 [style = invis, width = 0, label = \"\"]; 2 [label = 3]; C2 [style = invis, width = 0, label = \"\"]; 0 -> 1; 0 -> C0 [style = invis]; 0 -> R0 [style = invis]; {rank = same; 1 -> C0 -> R0 [style = invis]}; R0 [style = invis, width = 0, label = \"\"]; 1 -> 2; 1 -> C1 [style = invis]; 1 -> R1 [style = invis]; {rank = same; 2 -> C1 -> R1 [style = invis]}; R1 [style = invis, width = 0, label = \"\"]; 2 -> L2 [style = invis]; 2 -> C2 [style = invis]; 2 -> R2 [style = invis]; {rank = same; L2 -> C2 -> R2 [style = invis]}; L2 [style = invis, width = 0, label = \"\"]; R2 [style = invis, width = 0, label = \"\"] }")
  .then(function(element) {
    document.getElementById("example2Node0").appendChild(element);
  })
  .catch(error => {
    viz = new Viz();
    console.error(error);
  });
</script>

- node1 =

<div id="example2Node1" style="text-align: center"></div>
<script>
  var viz = new Viz();
  
  viz.renderSVGElement("digraph example2Node1 { 0 [label = 4]; C0 [style = invis, width = 0, label = \"\"]; 1 [label = 5]; C1 [style = invis, width = 0, label = \"\"]; 2 [label = 6]; C2 [style = invis, width = 0, label = \"\"]; 0 -> L0 [style = invis]; 0 -> C0 [style = invis]; 0 -> 1; {rank = same; L0 -> C0 -> 1 [style = invis]}; L0 [style = invis, width = 0, label = \"\"]; 1 -> L1 [style = invis]; 1 -> C1 [style = invis]; 1 -> 2; {rank = same; L1 -> C1 -> 2 [style = invis]}; L1 [style = invis, width = 0, label = \"\"]; 2 -> L2 [style = invis]; 2 -> C2 [style = invis]; 2 -> R2 [style = invis]; {rank = same; L2 -> C2 -> R2 [style = invis]}; L2 [style = invis, width = 0, label = \"\"]; R2 [style = invis, width = 0, label = \"\"] }")
  .then(function(element) {
    document.getElementById("example2Node1").appendChild(element);
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
  
  viz.renderSVGElement("digraph output { 0 [label = 5]; C0 [style = invis, width = 0, label = \"\"]; 1 [label = 2]; C1 [style = invis, width = 0, label = \"\"]; 2 [label = 5]; C2 [style = invis, width = 0, label = \"\"]; 3 [label = 3]; C3 [style = invis, width = 0, label = \"\"]; 4 [label = 6]; C4 [style = invis, width = 0, label = \"\"]; 0 -> 1; 0 -> C0 [style = invis]; 0 -> 2; {rank = same; 1 -> C0 -> 2 [style = invis]}; 1 -> 3; 1 -> C1 [style = invis]; 1 -> R1 [style = invis]; {rank = same; 3 -> C1 -> R1 [style = invis]}; R1 [style = invis, width = 0, label = \"\"]; 2 -> L2 [style = invis]; 2 -> C2 [style = invis]; 2 -> 4; {rank = same; L2 -> C2 -> 4 [style = invis]}; L2 [style = invis, width = 0, label = \"\"]; 3 -> L3 [style = invis]; 3 -> C3 [style = invis]; 3 -> R3 [style = invis]; {rank = same; L3 -> C3 -> R3 [style = invis]}; L3 [style = invis, width = 0, label = \"\"]; R3 [style = invis, width = 0, label = \"\"]; 4 -> L4 [style = invis]; 4 -> C4 [style = invis]; 4 -> R4 [style = invis]; {rank = same; L4 -> C4 -> R4 [style = invis]}; L4 [style = invis, width = 0, label = \"\"]; R4 [style = invis, width = 0, label = \"\"] }")
  .then(function(element) {
    document.getElementById("output").appendChild(element);
  })
  .catch(error => {
    viz = new Viz();
    console.error(error);
  });
</script>

**Explanation**

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Merging-Binary-Trees.cpp"></script>
