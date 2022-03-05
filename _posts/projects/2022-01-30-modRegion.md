---
title: "ModRegion: Base Modification Results Tool"
excerpt: "A CLI tool to quickly access, query and merge per-read base modification results from different software tools"
tags: bioinformatics
header:
  teaser: /assets/images/teaser-dna.jpg
featured: true
---

## Background

- [Epigenetics: DNA Methylation](https://en.wikipedia.org/wiki/DNA_methylation)
- [Nanopore DNA Sequencing](https://en.wikipedia.org/wiki/Nanopore_sequencing)
- Software tools to process raw nanopore sequencing data

## Overview

During my time at Walter and Eliza Hall Institute of Medical Research, I developed a tool to quickly access, query and merge per-read base modification results from different software tools.

`modRegion` is primarily written to quickly extract regional methylation statistics from tsv outputted from methylation callers and it now supports: [nanopolish](https://github.com/jts/nanopolish), [tombo](https://github.com/nanoporetech/tombo) and [deepsignal](https://github.com/bioinfomaticsCSU/deepsignal)

The motivation is that we are interested in fast querying output statistics over range of genomic positions at the single read resolution, and want to be able to have a common interface and coherent way of accessing the information as well as to save space on disk and on RAM.

`modRegion` allows users to extract, find overlaps of results with genes and plot per-read modification pattern over different regions.

Concretely, it has the following features:

- _extract_ - pulls out statistics in the region(s) supplied from one or more base modification tsvs (uses [lazy load](https://en.wikipedia.org/wiki/Lazy_loading) and supports gzipped tsvs)
- _overlap_ - finds statistics within ±overhang bases of genes
- _plot_ - accepts filtered output and plots (using ggplot2)

Read more about the tool at [https://github.com/yaeba/modRegion](https://github.com/yaeba/modRegion){:target="\_blank"}

## Example output

Attaching here is an example plot output produced by `modRegion` given the methylation status of parental strain and maternal strain near an [imprinting control region](https://en.wikipedia.org/wiki/Genomic_imprinting).

<image src="https://raw.githubusercontent.com/yaeba/modRegion/master/examples/icr_plot1.png" alt="Example Output of modRegion">
