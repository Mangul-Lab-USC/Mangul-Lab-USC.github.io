---
title: "Mangul Lab submits first preprint presenting app for managing high-throughput analyses via mobile device"
author: Lana Martin
<!-- member-page:  -->
tags:
  - method
  - preprints
  - software
---

## Mangul Lab submits first preprint presenting app for managing high-throughput analyses via mobile device

This week, Mangul Lab at USC released our first preprint, a paper that presents Telescope – a tool developed by our group for management of cloud-based high-throughput analyses!

In today’s world of big data, high-performance computational facilities are capable of processing considerable volumes of data. Computational resources capable of analyzing large data sets often lack an easy-to-use interface to guide the user in supervising and adjusting bioinformatics analysis in real-time. The rapidly growing array of big data sets and computational tools for analyzing big data has created demand for a continuous feedback loop that seamlessly integrates experimental biology and bioinformatics tools.

Jaqueline J. Brito (former researcher in the Institute of Mathematics and Computer Science at the University of Sao Paulo), Thiago Mosqueiro (former postdoctoral scholar in the QCBio Collaboratory), and Serghei Mangul (Assistant Professor in the USC School of Pharmacy) led a team in developing a tool that addressed this gap between bioinformatics and biological experimentation.

Telescope is a novel interactive protocol that interfaces with high-performance computational clusters to deliver an intuitive user interface to control and monitor in real time bioinformatics analyses. Users can use the tool to track with their smartphones any bioinformatics tools (e.g. GATK) or jobs submitted by specific platforms (e.g. Galaxy Project), displaying in real time partial outputs or possible warning and error messages.

Even novice users with minimal computational experience can take advantage of Telescope to simultaneously manage multiple analytical tasks, including:

1. tracking the progress and performance of running bioinformatics tools, displaying the current output in real-time in the browser;
2. interacting with the computational cluster with minimal effort, allowing cancellation and/or rescheduling of jobs with different parameters, or new jobs queuing
3. using archived statistics about previous jobs to estimate the resources necessary for future jobs.

Telescope natively operates with a simple and straightforward interface using Web 2.0 technology compatible with most tablets and smartphones, and the tool is designed to minimally interfere with the cluster’s performance. Telescope, which was tested on UCLA IDRE’s Hoffman2 Cluster, uses PBKDF cryptography to store and employ user credentials when establishing SSH connections.

Telescope is available at [https://github.com/Mangul-Lab-USC/telescope](https://github.com/Mangul-Lab-USC/telescope). 

Reference:

1. Jaqueline J Brito, Thiago Mosqueiro, Jeremy Rotman, Victor Xue, Douglas J Chapski, Juan De la Hoz, Paulo Matias, Lana S Martin, Alex Zelikovsky, Matteo Pellegrini, Serghei Mangul: Telescope: an interactive tool for managing large scale analysis from mobile devices. In: GigaScience, 9 (1), pp. giz163, 2020.
[https://arxiv.org/abs/1909.12469](https://arxiv.org/abs/1909.12469)


