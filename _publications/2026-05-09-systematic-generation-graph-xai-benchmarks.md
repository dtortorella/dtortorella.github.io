---
title: "A method for the systematic generation of graph XAI benchmarks via Weisfeiler–Leman coloring"
collection: publications
category: journals
permalink: /publication/2026-05-09-systematic-generation-graph-xai-benchmarks
excerpt: 'OpenGraphXAI benchmarks, with a method to guarantee ground truth learnability and uniqueness.'
date: 2026-05-09
venue: 'Data Mining and Knowledge Discovery'
paperurl: 'https://doi.org/10.1007/s10618-026-01212-z'
citation: 'M. Fontanesi, A. Micheli, M. Podda, D. Tortorella (2026). &quot;A method for the systematic generation of graph XAI benchmarks via Weisfeiler–Leman coloring.&quot; <i>Data Mining and Knowledge Discovery</i>, vol. 40(4), 42.'
---

![Graphical abstract](/images/2026-05-09-systematic-generation-graph-xai-benchmarks.png)

Graph neural networks (GNNs) have become the de facto model for learning from structured data. However, the decision-making process of GNNs remains opaque to the end user, which undermines their use in safety-critical applications. Several eXplainable Artificial Intelligence (XAI) techniques for graphs have been developed to address this major issue. Focusing on graph classification, these explainers identify subgraph motifs that explain predictions. Therefore, a robust benchmarking of graph explainers is required to ensure that the produced explanations are of high quality, i.e., aligned with the GNN’s decision process. However, current graph-XAI benchmarks are limited to simplistic synthetic datasets or a few real-world tasks curated by domain experts, hindering rigorous and reproducible evaluation, and consequently stalling progress in the field. To overcome these limitations, we propose a method to automate the construction of graph-XAI benchmarks from generic graph classification datasets. Our approach leverages the Weisfeiler–Leman (WL) color refinement algorithm to efficiently perform approximate subgraph matching and mine class-discriminating motifs, which serve as proxy ground-truth class explanations. At the same time, we ensure that these motifs can be learned by GNNs because their discriminating power aligns with WL expressiveness. This work also introduces the OpenGraphXAI benchmark suite, which consists of 15 ready-made graph-XAI datasets derived by applying our method to real-world molecular classification datasets. The suite is available to the public along with a codebase to generate over 2,000 additional graph-XAI benchmarks. Finally, we present a use case that illustrates how the suite can be used to assess the effectiveness of a selection of popular graph explainers, demonstrating the critical role of a sufficiently large benchmark collection for improving the significance of experimental results.

The OpenGraphXAI datasets and code are publicly available at [https://github.com/OpenGraphXAI/benchmarks](https://github.com/OpenGraphXAI/benchmarks).