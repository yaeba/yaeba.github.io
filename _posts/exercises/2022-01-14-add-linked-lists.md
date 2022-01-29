---
title: "Add Linked Lists"
tags: ["linked list"]
---

Given a singly linked list `l0` and another linked list `l1`, each representing a number with least significant digits first, return the summed linked list.

Note: Each value in the linked list is guaranteed to be between 0 and 9.

**Constraints**

- `n ≤ 100,000` where `n` is the number of nodes in `l0`
- `m ≤ 100,000` where `m` is the number of nodes in `l1`

[https://binarysearch.com/problems/Add-Linked-Lists](https://binarysearch.com/problems/Add-Linked-Lists){:target="\_blank"}

<script src="/assets/js/viz/viz.js"></script>
<script src="/assets/js/viz/lite.render.js"></script>

## Examples

### Example 1

**Input**

- l0 =

<div id="example1L0" style="text-align: center"></div>
<script>
  var viz = new Viz();
  
  viz.renderSVGElement("digraph example1L0 { 0 [label = 6]; 1 [label = 4]; 0->1; rankdir=LR }")
  .then(function(element) {
    document.getElementById("example1L0").appendChild(element);
  })
  .catch(error => {
    viz = new Viz();
    console.error(error);
  });
</script>

- l1 =

<div id="example1L1" style="text-align: center"></div>
<script>
  var viz = new Viz();
  
  viz.renderSVGElement("digraph example1L1 { 0 [label = 4]; 1 [label = 7]; 0->1; rankdir=LR }")
  .then(function(element) {
    document.getElementById("example1L1").appendChild(element);
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
  
  viz.renderSVGElement("digraph example1Output { 0 [label = 0]; 1 [label = 2]; 2 [label = 1]; 0->1->2; rankdir=LR }")
  .then(function(element) {
    document.getElementById("example1Output").appendChild(element);
  })
  .catch(error => {
    viz = new Viz();
    console.error(error);
  });
</script>

**Explanation**

This is `46 + 74 = 120`

## Solution

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Add-Linked-Lists.cpp"></script>
