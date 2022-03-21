---
title: "Swap Kth Node Values"
tags: ["linked list"]
---

You are given a singly linked list `node` and an integer `k`. Swap the value of the `k`-th (0-indexed) node from the end with the `k`-th node from the beginning.

**Constraints**

- `1 ≤ n ≤ 100,000` where `n` is the number of nodes in `node`
- `0 ≤ k < n`

[https://binarysearch.com/problems/Swap-Kth-Node-Values](https://binarysearch.com/problems/Swap-Kth-Node-Values){:target="\_blank"}

<script src="/assets/js/viz/viz.js"></script>
<script src="/assets/js/viz/lite.render.js"></script>

## Examples

### Example 1

**Input**

- node =

<div id="example1Node" style="text-align: center"></div>
<script>
  var viz = new Viz();
  
  viz.renderSVGElement("digraph example1Node { 0 [label = 1]; 1 [label = 2]; 2 [label = 3]; 3 [label = 4]; 4 [label = 5]; 5 [label = 6]; 0->1->2->3->4->5; rankdir=LR }")
  .then(function(element) {
    document.getElementById("example1Node").appendChild(element);
  })
  .catch(error => {
    viz = new Viz();
    console.error(error);
  });
</script>

- k = `1`

**Output**

- answer =

<div id="example1Output" style="text-align: center"></div>
<script>
  var viz = new Viz();
  
  viz.renderSVGElement("digraph example1Output { 0 [label = 1]; 1 [label = 5]; 2 [label = 3]; 3 [label = 4]; 4 [label = 2]; 5 [label = 6]; 0->1->2->3->4->5; rankdir=LR }")
  .then(function(element) {
    document.getElementById("example1Output").appendChild(element);
  })
  .catch(error => {
    viz = new Viz();
    console.error(error);
  });
</script>

**Explanation**

We swap `2` and `5`.

### Example 2

**Input**

- node =

<div id="example2Node" style="text-align: center"></div>
<script>
  var viz = new Viz();
  
  viz.renderSVGElement("digraph example2Node { 0 [label = 0]; 1 [label = 6]; 2 [label = 8]; 3 [label = 2]; 4 [label = 9]; 0->1->2->3->4; rankdir=LR }")
  .then(function(element) {
    document.getElementById("example2Node").appendChild(element);
  })
  .catch(error => {
    viz = new Viz();
    console.error(error);
  });
</script>

- k = `2`

**Output**

- answer =

<div id="example2Output" style="text-align: center"></div>
<script>
  var viz = new Viz();
  
  viz.renderSVGElement("digraph example2Output { 0 [label = 0]; 1 [label = 6]; 2 [label = 8]; 3 [label = 2]; 4 [label = 9]; 0->1->2->3->4; rankdir=LR }")
  .then(function(element) {
    document.getElementById("example2Output").appendChild(element);
  })
  .catch(error => {
    viz = new Viz();
    console.error(error);
  });
</script>

**Explanation**

We swap `8` with `8`.

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Swap-Kth-Node-Values.cpp"></script>
