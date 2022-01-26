---
title: "Subtree"
tags: ["tree"]
---

You are given two binary trees `root`, and `target`. Return whether `target` is a subtree of `root` — that is, whether there's a node in `root` that is identically same in values and structure as `root` including all of its descendants.

[https://binarysearch.com/problems/Subtree](https://binarysearch.com/problems/Subtree){:target="\_blank"}

<script src="/assets/js/viz/viz.js"></script>
<script src="/assets/js/viz/lite.render.js"></script>

## Examples

### Example 1

**Input**

- root =

<div id="example1Root" style="text-align: center"></div>
<script>
  var viz = new Viz();
  
  viz.renderSVGElement("digraph example1Root { 0 [label = 0]; C0 [style = invis, width = 0, label = \"\"]; 1 [label = 5]; C1 [style = invis, width = 0, label = \"\"]; 2 [label = 1]; C2 [style = invis, width = 0, label = \"\"]; 0 -> L0 [style = invis]; 0 -> C0 [style = invis]; 0 -> 1; {rank = same; L0 -> C0 -> 1 [style = invis]}; L0 [style = invis, width = 0, label = \"\"]; 1 -> 2; 1 -> C1 [style = invis]; 1 -> R1 [style = invis]; {rank = same; 2 -> C1 -> R1 [style = invis]}; R1 [style = invis, width = 0, label = \"\"]; 2 -> L2 [style = invis]; 2 -> C2 [style = invis]; 2 -> R2 [style = invis]; {rank = same; L2 -> C2 -> R2 [style = invis]}; L2 [style = invis, width = 0, label = \"\"]; R2 [style = invis, width = 0, label = \"\"] }")
  .then(function(element) {
    document.getElementById("example1Root").appendChild(element);
  })
  .catch(error => {
    viz = new Viz();
    console.error(error);
  });
</script>

- target =

<div id="example1Target" style="text-align: center"></div>
<script>
  var viz = new Viz();
  
  viz.renderSVGElement("digraph example1Target { 0 [label = 0]; C0 [style = invis, width = 0, label = \"\"]; 1 [label = 5]; C1 [style = invis, width = 0, label = \"\"]; 2 [label = 1]; C2 [style = invis, width = 0, label = \"\"]; 0 -> L0 [style = invis]; 0 -> C0 [style = invis]; 0 -> 1; {rank = same; L0 -> C0 -> 1 [style = invis]}; L0 [style = invis, width = 0, label = \"\"]; 1 -> 2; 1 -> C1 [style = invis]; 1 -> R1 [style = invis]; {rank = same; 2 -> C1 -> R1 [style = invis]}; R1 [style = invis, width = 0, label = \"\"]; 2 -> L2 [style = invis]; 2 -> C2 [style = invis]; 2 -> R2 [style = invis]; {rank = same; L2 -> C2 -> R2 [style = invis]}; L2 [style = invis, width = 0, label = \"\"]; R2 [style = invis, width = 0, label = \"\"] }")
  .then(function(element) {
    document.getElementById("example1Target").appendChild(element);
  })
  .catch(error => {
    viz = new Viz();
    console.error(error);
  });
</script>

**Output**

- answer = `True`

### Example 2

**Input**

- root =

<div id="example2Root" style="text-align: center"></div>
<script>
  var viz = new Viz();
  
  viz.renderSVGElement("digraph example2Root { 0 [label = 1]; C0 [style = invis, width = 0, label = \"\"]; 1 [label = 2]; C1 [style = invis, width = 0, label = \"\"]; 2 [label = 3]; C2 [style = invis, width = 0, label = \"\"]; 3 [label = 4]; C3 [style = invis, width = 0, label = \"\"]; 4 [label = 5]; C4 [style = invis, width = 0, label = \"\"]; 5 [label = 6]; C5 [style = invis, width = 0, label = \"\"]; 6 [label = 7]; C6 [style = invis, width = 0, label = \"\"]; 0 -> 1; 0 -> C0 [style = invis]; 0 -> 2; {rank = same; 1 -> C0 -> 2 [style = invis]}; 1 -> L1 [style = invis]; 1 -> C1 [style = invis]; 1 -> R1 [style = invis]; {rank = same; L1 -> C1 -> R1 [style = invis]}; L1 [style = invis, width = 0, label = \"\"]; R1 [style = invis, width = 0, label = \"\"]; 2 -> 3; 2 -> C2 [style = invis]; 2 -> 4; {rank = same; 3 -> C2 -> 4 [style = invis]}; 3 -> 5; 3 -> C3 [style = invis]; 3 -> R3 [style = invis]; {rank = same; 5 -> C3 -> R3 [style = invis]}; R3 [style = invis, width = 0, label = \"\"]; 4 -> L4 [style = invis]; 4 -> C4 [style = invis]; 4 -> 6; {rank = same; L4 -> C4 -> 6 [style = invis]}; L4 [style = invis, width = 0, label = \"\"]; 5 -> L5 [style = invis]; 5 -> C5 [style = invis]; 5 -> R5 [style = invis]; {rank = same; L5 -> C5 -> R5 [style = invis]}; L5 [style = invis, width = 0, label = \"\"]; R5 [style = invis, width = 0, label = \"\"]; 6 -> L6 [style = invis]; 6 -> C6 [style = invis]; 6 -> R6 [style = invis]; {rank = same; L6 -> C6 -> R6 [style = invis]}; L6 [style = invis, width = 0, label = \"\"]; R6 [style = invis, width = 0, label = \"\"] }")
  .then(function(element) {
    document.getElementById("example2Root").appendChild(element);
  })
  .catch(error => {
    viz = new Viz();
    console.error(error);
  });
</script>

- target =

<div id="example2Target" style="text-align: center"></div>
<script>
  var viz = new Viz();
  
  viz.renderSVGElement("digraph example2Target { 0 [label = 3]; C0 [style = invis, width = 0, label = \"\"]; 1 [label = 5]; C1 [style = invis, width = 0, label = \"\"]; 0 -> L0 [style = invis]; 0 -> C0 [style = invis]; 0 -> 1; {rank = same; L0 -> C0 -> 1 [style = invis]}; L0 [style = invis, width = 0, label = \"\"]; 1 -> L1 [style = invis]; 1 -> C1 [style = invis]; 1 -> R1 [style = invis]; {rank = same; L1 -> C1 -> R1 [style = invis]}; L1 [style = invis, width = 0, label = \"\"]; R1 [style = invis, width = 0, label = \"\"] }")
  .then(function(element) {
    document.getElementById("example2Target").appendChild(element);
  })
  .catch(error => {
    viz = new Viz();
    console.error(error);
  });
</script>

**Output**

- answer = `False`

### Example 3

**Input**

- root =

<div id="example3Root" style="text-align: center"></div>
<script>
  var viz = new Viz();
  
  viz.renderSVGElement("digraph example3Root { 0 [label = 1]; C0 [style = invis, width = 0, label = \"\"]; 1 [label = 2]; C1 [style = invis, width = 0, label = \"\"]; 2 [label = 3]; C2 [style = invis, width = 0, label = \"\"]; 3 [label = 4]; C3 [style = invis, width = 0, label = \"\"]; 4 [label = 5]; C4 [style = invis, width = 0, label = \"\"]; 5 [label = 6]; C5 [style = invis, width = 0, label = \"\"]; 6 [label = 7]; C6 [style = invis, width = 0, label = \"\"]; 0 -> 1; 0 -> C0 [style = invis]; 0 -> 2; {rank = same; 1 -> C0 -> 2 [style = invis]}; 1 -> L1 [style = invis]; 1 -> C1 [style = invis]; 1 -> R1 [style = invis]; {rank = same; L1 -> C1 -> R1 [style = invis]}; L1 [style = invis, width = 0, label = \"\"]; R1 [style = invis, width = 0, label = \"\"]; 2 -> 3; 2 -> C2 [style = invis]; 2 -> 4; {rank = same; 3 -> C2 -> 4 [style = invis]}; 3 -> 5; 3 -> C3 [style = invis]; 3 -> R3 [style = invis]; {rank = same; 5 -> C3 -> R3 [style = invis]}; R3 [style = invis, width = 0, label = \"\"]; 4 -> L4 [style = invis]; 4 -> C4 [style = invis]; 4 -> 6; {rank = same; L4 -> C4 -> 6 [style = invis]}; L4 [style = invis, width = 0, label = \"\"]; 5 -> L5 [style = invis]; 5 -> C5 [style = invis]; 5 -> R5 [style = invis]; {rank = same; L5 -> C5 -> R5 [style = invis]}; L5 [style = invis, width = 0, label = \"\"]; R5 [style = invis, width = 0, label = \"\"]; 6 -> L6 [style = invis]; 6 -> C6 [style = invis]; 6 -> R6 [style = invis]; {rank = same; L6 -> C6 -> R6 [style = invis]}; L6 [style = invis, width = 0, label = \"\"]; R6 [style = invis, width = 0, label = \"\"] }")
  .then(function(element) {
    document.getElementById("example3Root").appendChild(element);
  })
  .catch(error => {
    viz = new Viz();
    console.error(error);
  });
</script>

- target =

<div id="example3Target" style="text-align: center"></div>
<script>
  var viz = new Viz();
  
  viz.renderSVGElement("digraph example3Target { 0 [label = 3]; C0 [style = invis, width = 0, label = \"\"]; 1 [label = 4]; C1 [style = invis, width = 0, label = \"\"]; 2 [label = 5]; C2 [style = invis, width = 0, label = \"\"]; 3 [label = 6]; C3 [style = invis, width = 0, label = \"\"]; 4 [label = 7]; C4 [style = invis, width = 0, label = \"\"]; 0 -> 1; 0 -> C0 [style = invis]; 0 -> 2; {rank = same; 1 -> C0 -> 2 [style = invis]}; 1 -> 3; 1 -> C1 [style = invis]; 1 -> R1 [style = invis]; {rank = same; 3 -> C1 -> R1 [style = invis]}; R1 [style = invis, width = 0, label = \"\"]; 2 -> L2 [style = invis]; 2 -> C2 [style = invis]; 2 -> 4; {rank = same; L2 -> C2 -> 4 [style = invis]}; L2 [style = invis, width = 0, label = \"\"]; 3 -> L3 [style = invis]; 3 -> C3 [style = invis]; 3 -> R3 [style = invis]; {rank = same; L3 -> C3 -> R3 [style = invis]}; L3 [style = invis, width = 0, label = \"\"]; R3 [style = invis, width = 0, label = \"\"]; 4 -> L4 [style = invis]; 4 -> C4 [style = invis]; 4 -> R4 [style = invis]; {rank = same; L4 -> C4 -> R4 [style = invis]}; L4 [style = invis, width = 0, label = \"\"]; R4 [style = invis, width = 0, label = \"\"] }")
  .then(function(element) {
    document.getElementById("example3Target").appendChild(element);
  })
  .catch(error => {
    viz = new Viz();
    console.error(error);
  });
</script>

**Output**

- answer = `True`

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Subtree.cpp"></script>
