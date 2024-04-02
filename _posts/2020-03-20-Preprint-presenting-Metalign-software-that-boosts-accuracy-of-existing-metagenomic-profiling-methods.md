---
title: "Mangul Lab submits preprint presenting Metalign, software that boosts accuracy of existing metagenomic profiling methods"
author: Lana Martin
<!-- member-page:  -->
tags:
  - Preprints 
  - Method
  - Software
---

## Mangul Lab submits preprint presenting Metalign, software that boosts accuracy of existing metagenomic profiling methods

Mangul Lab at USC shared a new preprint which presents Metalign – a tool developed by our group that significantly improves the taxonomic profiling accuracy of a metagenomic sample.

Microorganisms play a critical role in almost every natural setting, including soil, ocean water, and the human body. The field of metagenomics, driven by modern high-throughput sequencing techniques, can identify whole microbial genomes recovered directly from their host environment and is well-poised to advance our understanding of microbiomes. However, current methods for conducting metagenomic profiling of such microbial genomes present frustrating trade-offs between recall (i.e., rate of false negatives) and precision.

Nathan LaPierre (PhD student in Computer Science at UCLA), Mohammed Alser (Senior Researcher and Lecturer of computer architecture and bioinformatics at the Department of Computer Science, ETH Zürich), Eleazar Eskin (Professor of Computational Medicine, Computer Science, and Human Genetics at UCLA), and David Koslicki (Associate Professor of Computer Science and Engineering, Biology, and the Huck Institute of the Life Sciences at Penn State), addressed this concern with Metalign, which performs efficient alignment-based metagenomic profiling. Alignment-based profiling is regarded as highly accurate, but aligning millions of reads against a reference database of tens to hundreds of gigabytes (GB) in size is computationally infeasible.

To avoid this issue, Metalign employs a high-speed, high-recall pre-filtering method based on the mathematical concept of Containment Min Hash, which identifies a small number of candidate organisms that are potentially in the sample and creates a subset database consisting of these organisms. The authors applied Metalign to simulated and real world datasets and found an increase in precision and/or recall rate relative to existing state-of-the-art methods.

Metalign’s demonstrated performance is not just an incremental improvement—the authors show that Metalign outperforms all other methods in both prediction of presence/absence of species and relative abundance estimation. No other method achieved above 50% for both precision and recall, while Metalign achieved roughly 80% for both!

Metalign is available at [https://github.com/nlapier2/Metalign](https://github.com/nlapier2/Metalign).

Reference:

Nathan LaPierre, Mohammed Alser, Eleazar Eskin, David Koslicki, Serghei Mangul: Metalign: Efficient alignment-based metagenomic profiling via containment min hash. In: bioRxiv, 2020.
[https://www.biorxiv.org/content/10.1101/2020.01.17.910521v1.full](https://www.biorxiv.org/content/10.1101/2020.01.17.910521v1.full)



