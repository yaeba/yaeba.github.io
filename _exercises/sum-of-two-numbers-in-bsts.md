---
title: "Sum of Two Numbers in BSTs"
tags: ["tree"]
---

You are given two binary search trees `a` and `b` and an integer `target`. Return whether there's a number in `a` and a number in `b` such that their sum equals to `target`

**Constraints**

- `n ≤ 100,000` where `n` is the number of nodes in `a`
- `m ≤ 100,000` where `m` is the number of nodes in `b`

[https://binarysearch.com/problems/Sum-of-Two-Numbers-in-BSTs](https://binarysearch.com/problems/Sum-of-Two-Numbers-in-BSTs){:target="\_blank"}

<script src="/assets/js/viz/viz.js"></script>
<script src="/assets/js/viz/lite.render.js"></script>

## Examples

### Example 1

**Input**

- a =

<div id="example1A" style="text-align: center"></div>
<script>
  var viz = new Viz();
  
  viz.renderSVGElement("digraph example1A { 0 [label = 5]; C0 [style = invis, width = 0, label = \"\"]; 1 [label = 3]; C1 [style = invis, width = 0, label = \"\"]; 2 [label = 7]; C2 [style = invis, width = 0, label = \"\"]; 0 -> 1; 0 -> C0 [style = invis]; 0 -> 2; {rank = same; 1 -> C0 -> 2 [style = invis]}; 1 -> L1 [style = invis]; 1 -> C1 [style = invis]; 1 -> R1 [style = invis]; {rank = same; L1 -> C1 -> R1 [style = invis]}; L1 [style = invis, width = 0, label = \"\"]; R1 [style = invis, width = 0, label = \"\"]; 2 -> L2 [style = invis]; 2 -> C2 [style = invis]; 2 -> R2 [style = invis]; {rank = same; L2 -> C2 -> R2 [style = invis]}; L2 [style = invis, width = 0, label = \"\"]; R2 [style = invis, width = 0, label = \"\"] }")
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
  
  viz.renderSVGElement("digraph example1B { 0 [label = 4]; C0 [style = invis, width = 0, label = \"\"]; 1 [label = 2]; C1 [style = invis, width = 0, label = \"\"]; 2 [label = 8]; C2 [style = invis, width = 0, label = \"\"]; 0 -> 1; 0 -> C0 [style = invis]; 0 -> 2; {rank = same; 1 -> C0 -> 2 [style = invis]}; 1 -> L1 [style = invis]; 1 -> C1 [style = invis]; 1 -> R1 [style = invis]; {rank = same; L1 -> C1 -> R1 [style = invis]}; L1 [style = invis, width = 0, label = \"\"]; R1 [style = invis, width = 0, label = \"\"]; 2 -> L2 [style = invis]; 2 -> C2 [style = invis]; 2 -> R2 [style = invis]; {rank = same; L2 -> C2 -> R2 [style = invis]}; L2 [style = invis, width = 0, label = \"\"]; R2 [style = invis, width = 0, label = \"\"] }")
  .then(function(element) {
    document.getElementById("example1B").appendChild(element);
  })
  .catch(error => {
    viz = new Viz();
    console.error(error);
  });
</script>

- target = `9`

**Output**

- answer = `True`

**Explanation**

We can pick `7` from `a` and `2` from `b`.

### Example 2

**Input**

- a =

<div id="example2A" style="text-align: center"></div>
<script>
  var viz = new Viz();
  
  viz.renderSVGElement("digraph example2A { 0 [label = 5]; C0 [style = invis, width = 0, label = \"\"]; 1 [label = 3]; C1 [style = invis, width = 0, label = \"\"]; 2 [label = 7]; C2 [style = invis, width = 0, label = \"\"]; 0 -> 1; 0 -> C0 [style = invis]; 0 -> 2; {rank = same; 1 -> C0 -> 2 [style = invis]}; 1 -> L1 [style = invis]; 1 -> C1 [style = invis]; 1 -> R1 [style = invis]; {rank = same; L1 -> C1 -> R1 [style = invis]}; L1 [style = invis, width = 0, label = \"\"]; R1 [style = invis, width = 0, label = \"\"]; 2 -> L2 [style = invis]; 2 -> C2 [style = invis]; 2 -> R2 [style = invis]; {rank = same; L2 -> C2 -> R2 [style = invis]}; L2 [style = invis, width = 0, label = \"\"]; R2 [style = invis, width = 0, label = \"\"] }")
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
  
  viz.renderSVGElement("digraph example2B { 0 [label = 4]; C0 [style = invis, width = 0, label = \"\"]; 1 [label = 2]; C1 [style = invis, width = 0, label = \"\"]; 2 [label = 8]; C2 [style = invis, width = 0, label = \"\"]; 0 -> 1; 0 -> C0 [style = invis]; 0 -> 2; {rank = same; 1 -> C0 -> 2 [style = invis]}; 1 -> L1 [style = invis]; 1 -> C1 [style = invis]; 1 -> R1 [style = invis]; {rank = same; L1 -> C1 -> R1 [style = invis]}; L1 [style = invis, width = 0, label = \"\"]; R1 [style = invis, width = 0, label = \"\"]; 2 -> L2 [style = invis]; 2 -> C2 [style = invis]; 2 -> R2 [style = invis]; {rank = same; L2 -> C2 -> R2 [style = invis]}; L2 [style = invis, width = 0, label = \"\"]; R2 [style = invis, width = 0, label = \"\"] }")
  .then(function(element) {
    document.getElementById("example2B").appendChild(element);
  })
  .catch(error => {
    viz = new Viz();
    console.error(error);
  });
</script>

- target = `4`

**Output**

- answer = `False`

**Explanation**

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Sum-of-Two-Numbers-in-BSTs.cpp"></script>
