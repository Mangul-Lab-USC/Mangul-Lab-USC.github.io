---
title: "Mangul Lab submits preprint of a WGS-based structural variant callers benchmarking study"
author: Lana Martin
<!-- member-page:  -->
tags:
  - Benchmarking-study
  - Preprints
---

## Mangul Lab submits preprint of a WGS-based structural variant callers benchmarking study

Mangul Lab at USC shared a new preprint which presents a benchmarking study of structural variant (SV) callers – computational tools for identifying genomic regions that have altered DNA and may be implicated in various diseases and disorders.

Varuni Sarwal, alumnus of Serghei’s group at UCLA, is the first author of “A comprehensive benchmarking of WGS-based structural variant callers,” and led this project. Angela (one of our Ph.D. students) collaborated with Varuni, Serghei, and our colleagues at UCLA: [Eleazar Eskin](), [Jonathan Flint](), and [Margaret G. Distler]() to assess currently available SV callers.


Comparison of inferred deletions across SV callers on mouse data.

As with many Mangul Lab projects, several of our undergraduate students are co-authors and contributed to benchmarking the SV callers: Ram Ayyala, Sei Chang, Niko Darci-Maher, Russell Littman, and Rahul Chikka. In addition, Emily Wesel worked on this project while a high school scholar in the B.I.G. Summer program, and Jacqueline Castellanos made substantial contributions while a community college student scholar in [B.I.G. Summer]().

Over the last decade, computational biology researchers have developed a plethora of SV-detection methods for use in whole-genome sequencing (WGS) data, but the relative performance of these tools is unknown. This current lack of comprehensive benchmarking makes it impossible for biomedical researchers to adequately compare the performance of SV callers.

In response to this pressing need for a comprehensive gold standard dataset, our preprint presents a rigorous assessment of both sensitivity and precision of SV-detection tools when applied to mouse data. We used a set of homozygous deletions present in inbred mouse chromosomes to test the ability of 12 currently-available SV callers to detect deletions. (While more than 50 SV callers exist, remaining tools could not be installed—a common problem with academic software development, which our lab explored in a [previously published PLoS Biology paper]().)

Our study finds that the performance of SV callers on mouse WGS data is variable:

1. 50% of tools report fewer deletions than are known to be present in the sample
2. When true deletions are 3710, the number of deletions detected range from 899 to 82,225
3. 61.5% of tools underestimate the true size of SVs
4. Few tools were able to maintain a good balance between precision and sensitivity

We envision that future SV-caller methods should enable detection of deletions with precise coordinates. We hope our benchmarking study helps researchers better select an SV caller for any given data set and analytical task!

We note that benchmarking is a very accessible project for undergraduates—and even high schoolers—to make meaningful contributions toward, due to a large number of routine tasks which provide great training. If you are still hesitant to involve undergraduates in your research, please check out [our paper in Nature Biotechnology](https://www.nature.com/articles/nbt.4113), which provides recommendations.

Read our preprint available on [bioRxiv](https://www.biorxiv.org/content/10.1101/2020.04.16.045120v2).


Varuni Sarwal, Sebastian Niehus, Ram Ayyala, Sei Chang, Angela Lu, Nicholas Darci-Maher, Russell Jared Littman, Emily Wesel, Jacqueline Castellanos, Rahul Chikka, Margaret G Distler, Eleazar Eskin, Jonathan Flint, Serghei Mangul: A comprehensive benchmarking of WGS-based structural variant callers. In: bioRxiv, 2020.
[https://www.biorxiv.org/content/10.1101/2020.04.16.045120v2](https://www.biorxiv.org/content/10.1101/2020.04.16.045120v2)


