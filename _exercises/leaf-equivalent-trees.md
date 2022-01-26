---
title: "Leaf Equivalent Trees"
tags: ["tree"]
---

Given two binary trees `root0` and `root1`, return whether the sequence of leaves left-to-right in both trees are the same.

**Constraints**

- `n ≤ 100,000` where `n` is the number of nodes in `root0`
- `m ≤ 100,000` where `m` is the number of nodes in `root1`

[https://binarysearch.com/problems/Leaf-Equivalent-Trees](https://binarysearch.com/problems/Leaf-Equivalent-Trees){:target="\_blank"}

<script src="/assets/js/viz/viz.js"></script>
<script src="/assets/js/viz/lite.render.js"></script>

## Examples

### Example 1

**Input**

- root0 =

<div id="example1Root0" style="text-align: center"></div>
<script>
  var viz = new Viz();
  
  viz.renderSVGElement("digraph example1Root0 { 0 [label = 1]; C0 [style = invis, width = 0, label = \"\"]; 1 [label = 2]; C1 [style = invis, width = 0, label = \"\"]; 2 [label = 3]; C2 [style = invis, width = 0, label = \"\"]; 0 -> 1; 0 -> C0 [style = invis]; 0 -> 2; {rank = same; 1 -> C0 -> 2 [style = invis]}; 1 -> L1 [style = invis]; 1 -> C1 [style = invis]; 1 -> R1 [style = invis]; {rank = same; L1 -> C1 -> R1 [style = invis]}; L1 [style = invis, width = 0, label = \"\"]; R1 [style = invis, width = 0, label = \"\"]; 2 -> L2 [style = invis]; 2 -> C2 [style = invis]; 2 -> R2 [style = invis]; {rank = same; L2 -> C2 -> R2 [style = invis]}; L2 [style = invis, width = 0, label = \"\"]; R2 [style = invis, width = 0, label = \"\"] }")
  .then(function(element) {
    document.getElementById("example1Root0").appendChild(element);
  })
  .catch(error => {
    viz = new Viz();
    console.error(error);
  });
</script>

- root1 =

<div id="example1Root1" style="text-align: center"></div>
<script>
  var viz = new Viz();
  
  viz.renderSVGElement("digraph example1Root1 { 0 [label = 1]; C0 [style = invis, width = 0, label = \"\"]; 1 [label = 3]; C1 [style = invis, width = 0, label = \"\"]; 2 [label = 2]; C2 [style = invis, width = 0, label = \"\"]; 0 -> 1; 0 -> C0 [style = invis]; 0 -> 2; {rank = same; 1 -> C0 -> 2 [style = invis]}; 1 -> L1 [style = invis]; 1 -> C1 [style = invis]; 1 -> R1 [style = invis]; {rank = same; L1 -> C1 -> R1 [style = invis]}; L1 [style = invis, width = 0, label = \"\"]; R1 [style = invis, width = 0, label = \"\"]; 2 -> L2 [style = invis]; 2 -> C2 [style = invis]; 2 -> R2 [style = invis]; {rank = same; L2 -> C2 -> R2 [style = invis]}; L2 [style = invis, width = 0, label = \"\"]; R2 [style = invis, width = 0, label = \"\"] }")
  .then(function(element) {
    document.getElementById("example1Root1").appendChild(element);
  })
  .catch(error => {
    viz = new Viz();
    console.error(error);
  });
</script>

**Output**

- answer = `False`

**Explanation**

The left tree has `[2, 3]` and right has `[3, 2]`

### Example 2

**Input**

- root0 =

<div id="example2Root0" style="text-align: center"></div>
<script>
  var viz = new Viz();
  
  viz.renderSVGElement("digraph example2Root0 { 0 [label = 0]; C0 [style = invis, width = 0, label = \"\"]; 1 [label = 3]; C1 [style = invis, width = 0, label = \"\"]; 2 [label = 1]; C2 [style = invis, width = 0, label = \"\"]; 3 [label = 2]; C3 [style = invis, width = 0, label = \"\"]; 4 [label = 1]; C4 [style = invis, width = 0, label = \"\"]; 0 -> 1; 0 -> C0 [style = invis]; 0 -> 2; {rank = same; 1 -> C0 -> 2 [style = invis]}; 1 -> L1 [style = invis]; 1 -> C1 [style = invis]; 1 -> 3; {rank = same; L1 -> C1 -> 3 [style = invis]}; L1 [style = invis, width = 0, label = \"\"]; 2 -> 4; 2 -> C2 [style = invis]; 2 -> R2 [style = invis]; {rank = same; 4 -> C2 -> R2 [style = invis]}; R2 [style = invis, width = 0, label = \"\"]; 3 -> L3 [style = invis]; 3 -> C3 [style = invis]; 3 -> R3 [style = invis]; {rank = same; L3 -> C3 -> R3 [style = invis]}; L3 [style = invis, width = 0, label = \"\"]; R3 [style = invis, width = 0, label = \"\"]; 4 -> L4 [style = invis]; 4 -> C4 [style = invis]; 4 -> R4 [style = invis]; {rank = same; L4 -> C4 -> R4 [style = invis]}; L4 [style = invis, width = 0, label = \"\"]; R4 [style = invis, width = 0, label = \"\"] }")
  .then(function(element) {
    document.getElementById("example2Root0").appendChild(element);
  })
  .catch(error => {
    viz = new Viz();
    console.error(error);
  });
</script>

- root1 =

<div id="example2Root1" style="text-align: center"></div>
<script>
  var viz = new Viz();
  
  viz.renderSVGElement("digraph example2Root1 { 0 [label = 0]; C0 [style = invis, width = 0, label = \"\"]; 1 [label = 1]; C1 [style = invis, width = 0, label = \"\"]; 2 [label = 3]; C2 [style = invis, width = 0, label = \"\"]; 3 [label = 2]; C3 [style = invis, width = 0, label = \"\"]; 4 [label = 1]; C4 [style = invis, width = 0, label = \"\"]; 0 -> 1; 0 -> C0 [style = invis]; 0 -> 2; {rank = same; 1 -> C0 -> 2 [style = invis]}; 1 -> L1 [style = invis]; 1 -> C1 [style = invis]; 1 -> 3; {rank = same; L1 -> C1 -> 3 [style = invis]}; L1 [style = invis, width = 0, label = \"\"]; 2 -> L2 [style = invis]; 2 -> C2 [style = invis]; 2 -> 4; {rank = same; L2 -> C2 -> 4 [style = invis]}; L2 [style = invis, width = 0, label = \"\"]; 3 -> L3 [style = invis]; 3 -> C3 [style = invis]; 3 -> R3 [style = invis]; {rank = same; L3 -> C3 -> R3 [style = invis]}; L3 [style = invis, width = 0, label = \"\"]; R3 [style = invis, width = 0, label = \"\"]; 4 -> L4 [style = invis]; 4 -> C4 [style = invis]; 4 -> R4 [style = invis]; {rank = same; L4 -> C4 -> R4 [style = invis]}; L4 [style = invis, width = 0, label = \"\"]; R4 [style = invis, width = 0, label = \"\"] }")
  .then(function(element) {
    document.getElementById("example2Root1").appendChild(element);
  })
  .catch(error => {
    viz = new Viz();
    console.error(error);
  });
</script>

**Output**

- answer = `True`

**Explanation**

Both trees have leaves `[2, 1]`.

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Leaf-Equivalent-Trees.py"></script>
