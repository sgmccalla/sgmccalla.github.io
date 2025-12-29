---
title: "scRNA-seq Network Inference Benchmarking"
collection: projects
permalink: /projects/scrnaseq-net-inference/
date: 2023-01-10

excerpt: "Benchmarking gene regulatory network inference methods on bulk and single-cell RNA-seq to assess accuracy, recoverable edges, and predictable transcription factors."
---

![Workflow overview for scRNA-seq network inference benchmarking](/assets/img/projects/scrnaseq-net-inference.png)

This project benchmarks gene regulatory network inference methods for scRNA-seq, comparing **11 algorithms** across **7 published datasets** (human, mouse, yeast) and multiple gold standards and metrics, including scalability (time, memory) and network recovery. Key findings: although overall recovery of global metrics (F-score and AUPR) is limited, methods capture biologically meaningful regulator–target interactions, and incorporating **prior knowledge** plus **transcription factor activity** estimation improves overall performance, while imputation did not help and can be detrimental.

- **Paper:** <https://academic.oup.com/g3journal/article/13/3/jkad004/6982776>
- **Code:** <https://github.com/Roy-lab/scRNAseq_NetInference>
