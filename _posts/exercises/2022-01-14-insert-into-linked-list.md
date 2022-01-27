---
title: "Insert Into Linked List"
---

You are given a singly linked list `head` as well as integers `pos` and `val`. Insert a new node with value `val` before index `pos` of `head`.

**Constraints**

- `1 ≤ n ≤ 100,000` where `n` is the number of nodes in `head`
- `0 ≤ pos ≤ n`

[https://binarysearch.com/problems/Insert-Into-Linked-List](https://binarysearch.com/problems/Insert-Into-Linked-List){:target="\_blank"}

<script src="/assets/js/viz/viz.js"></script>
<script src="/assets/js/viz/lite.render.js"></script>

## Examples

### Example 1

**Input**

- head =

<div id="example1Head" style="text-align: center"></div>
<script>
  var viz = new Viz();
  
  viz.renderSVGElement("digraph example1Head { 0 [label = 1]; 1 [label = 3]; 2 [label = 5]; 3 [label = 7]; 0->1->2->3; rankdir=LR }")
  .then(function(element) {
    document.getElementById("example1Head").appendChild(element);
  })
  .catch(error => {
    viz = new Viz();
    console.error(error);
  });
</script>

- pos = `2`
- val = `9`

**Output**

- answer =

<div id="output" style="text-align: center"></div>
<script>
  var viz = new Viz();
  
  viz.renderSVGElement("digraph output { 0 [label = 1]; 1 [label = 3]; 2 [label = 9]; 3 [label = 5]; 4 [label = 7]; 0->1->2->3->4; rankdir=LR }")
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

- head =

<div id="example2Head" style="text-align: center"></div>
<script>
  var viz = new Viz();
  
  viz.renderSVGElement("digraph example2Head { 0 [label = 1]; 0; rankdir=LR }")
  .then(function(element) {
    document.getElementById("example2Head").appendChild(element);
  })
  .catch(error => {
    viz = new Viz();
    console.error(error);
  });
</script>

- pos = `0`
- val = `3`

**Output**

- answer =

<div id="output" style="text-align: center"></div>
<script>
  var viz = new Viz();
  
  viz.renderSVGElement("digraph output { 0 [label = 3]; 1 [label = 1]; 0->1; rankdir=LR }")
  .then(function(element) {
    document.getElementById("output").appendChild(element);
  })
  .catch(error => {
    viz = new Viz();
    console.error(error);
  });
</script>

**Explanation**

### Example 3

**Input**

- head =

<div id="example3Head" style="text-align: center"></div>
<script>
  var viz = new Viz();
  
  viz.renderSVGElement("digraph example3Head { 0 [label = 2]; 0; rankdir=LR }")
  .then(function(element) {
    document.getElementById("example3Head").appendChild(element);
  })
  .catch(error => {
    viz = new Viz();
    console.error(error);
  });
</script>

- pos = `1`
- val = `5`

**Output**

- answer =

<div id="output" style="text-align: center"></div>
<script>
  var viz = new Viz();
  
  viz.renderSVGElement("digraph output { 0 [label = 2]; 1 [label = 5]; 0->1; rankdir=LR }")
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

<script src="https://gist.github.com/yaeba/16da7be5123724fcf6eccc25581cef5a.js?file=Insert-Into-Linked-List.cpp"></script>
