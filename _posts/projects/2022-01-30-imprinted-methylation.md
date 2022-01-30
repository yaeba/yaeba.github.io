---
title: "Imprinted Methylation"
excerpt: "Detecting imprinted methylation from Nanopore sequencing reads"
tags: bioinformatics
---

In this project, I reproduced the results from **Gigante et al., 2018: Using long-read sequencing to detect imprinted DNA methylation** (research paper [here](https://academic.oup.com/nar/article/47/8/e46/5356940)).

Briefly, with newer version of basecaller and [tombo](https://github.com/nanoporetech/tombo) methylation caller, I validated the results from analysis of original author's work - successfully identified known imprinting control regions (ICRs) as well as some novel differentially methylated regions.

For more detailed information, please see the original author's work at his [repo](https://github.com/scottgigante/haplotyped-methylome).

This repo contains scripts and notebooks used for:

- mapping reads to reference genome
- haplotyping reads (to paternal or maternal strain)
- tombo resquiggling
- call methylation with tombo and nanopolish
- plot per-read methylation patterns at known ICRs
- detect novel differentially methylated regions

## Example output from notebook

<image src="https://raw.githubusercontent.com/yaeba/imprinted_methylation/master/examples/example2.png" alt="Example Notebook Output">
