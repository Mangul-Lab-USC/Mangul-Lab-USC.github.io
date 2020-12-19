---
title: "Mangul Lab publishes fifth paper presenting a novel method for profiling immunoglobulin (Ig) receptor repertoires from RNA-Seq"
author: Lana Martin
<!-- member-page:  -->
tags:
  - method
  - publication
  - software
---

## Mangul Lab publishes fifth paper presenting a novel method for profiling immunoglobulin (Ig) receptor repertoires from RNA-Seq

SMangul Lab at USC published a paper presenting ImReP – a novel computational tool that uses RNA-Seq data for rapid and accurate profiling of the immunoglobulin (Ig) repertoire.

RNA-Seq data presents a unique opportunity to examine the adaptive immune system by profiling the both light and heavy chains that compose the Ig repertoire. Commonly-used assay-based approaches are able to provide a detailed view of the heavy chain, which interacts with other immune cells and controls most of the biological functions of antibodies. However, standard approaches are not capable of profiling the light chain, which is more likely to have public receptors (shared across more than one individual) that are shared across tissue types—and more likely to reflect the true diversity of the Ig repertoire.

In response to a need for developing a comprehensive account of the light and heavy chains in an Ig repertoire, we developed ImReP—an alignment-free computational method for profiling the Ig repertoire from regular RNA-Seq data. ImReP is capable of efficiently extracting receptor-derived reads from RNA-Seq data and accurately assembling Ig clonotypes, defined as distinct amino acid sequences of complementarity-determining region 3 (CDR3).

Our paper demonstrates that bulk RNA-Seq is a suitable technology for measuring the individual adaptive immune repertoire. In our validation experiments, ImReP is able to capture 69% of the immune repertoire obtained by BCR-Seq. Using ImReP, created a systematic atlas of Ig sequences across a broad range of tissue types, most of which were previously unstudied for Ig repertoires. We also examine the compositional similarities of clonal populations between the tissues to track the flow of Ig clonotypes across immune-related tissues, including secondary lymphoid and organs that encompass mucosal, exocrine, and endocrine sites.

Serghei began working on this project while a postdoctoral scholar in [Eleazar Eskin’s computational genomics lab at UCLA](http://zarlab.cs.ucla.edu/). [Igor Mandric](https://github.com/mandricigor) (postdoc at UCLA) developed the tool, and the project was a group effort involving colleagues Sagiv Shifman (faculty at The Hebrew University of Jerusalem), [Noah Zaitlen](https://www.uclahealth.org/neurology/dr-noah-zaitlen-efficient-estimation-and-applications-of-cross-validated-genetic-predictions-to-polygenic-risk-scores-and-linear-mixed-models) (faculty formerly at UCSF, now faculty at UCLA), [Maura Rossetti](https://www.uclahealth.org/pathology/maura-rossetti-phd) (faculty at UCLA), [Mark Ansel](https://ansel.ucsf.edu/people/mark-ansel-phd) (faculty at UCSF), and Eleazar Eskin (faculty at UCLA).

As with many Mangul Lab projects, several of our undergraduate students are co-authors and contributed to the development and implementation of the method: Jeremy Rotman (now a Software Engineer in our group), Harry Yang, Benjamin Statz, Doug Yao, and Will Van Der Wey. Ben, Jeremy, and Will worked on this project while scholars in the [B.I.G. Summer program](https://qcb.ucla.edu/big-summer/).

In addition, as with all Mangul Lab projects, in effort to promote scientific reproducibility and data availability all the data and code necessary to reproduce figures are available on GitHub: [https://github.com/Mangul-Lab-USC/ImReP_publication](https://github.com/Mangul-Lab-USC/ImReP_publication). We owe credit to Jeremy for organizing data on the GitHub! The software itself, developed by Igor Mandric, is also available on GitHub [https://github.com/Mangul-Lab-USC/imrep](https://github.com/Mangul-Lab-USC/imrep).

Our proposed approach provides a useful tool for mining large-scale RNA-Seq datasets for the study of Ig receptor repertoires. We hope that computational bioscience and life- and biomedical-science researchers find ImReP useful!

1. Check out the [software package on our lab GitHub](https://github.com/Mangul-Lab-USC/imrep).
2. Read our [paper available at Nature Communications](https://www.nature.com/articles/s41467-020-16857-7).

Igor Mandric, Jeremy Rotman, Harry Taegyun Yang, Nicolas Strauli, Dennis Montoya, Will Van Der Lay, Jiem R Ronas, Benjamin Statz, Douglas Yao, Velislava Petrova, Alex Zelikovsky, Roberto Spreafico, Sagiv Shifman, Noah Zaitlen, Maura Rossetti, K. Mark Ansel, Eleazar Eskin, Serghei Mangul: Profiling immunoglobulin repertoires across multiple human tissues using RNA sequencing. In: Nature Communications, 11 (3126), 2020.
[https://doi.org/10.1038/s41467-020-16857-7](https://doi.org/10.1038/s41467-020-16857-7)


