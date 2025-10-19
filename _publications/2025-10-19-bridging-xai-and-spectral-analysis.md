---
title: "Bridging XAI and spectral analysis to investigate the inductive biases of deep graph networks"
collection: publications
category: journals
permalink: /publication/2025-10-19-bridging-xai-and-spectral-analysis
excerpt: 'We apply graph signal processing to node importances of XAI explanations to refine the characterization of DGN inductive biases.'
date: 2025-10-19
venue: 'Machine Learning'
paperurl: 'https://doi.org/10.1007/s10994-025-06884-0'
citation: 'M. Fontanesi, A. Micheli, M. Podda, D. Tortorella (2025). &quot;Bridging XAI and spectral analysis to investigate the inductive biases of deep graph networks.&quot; <i>Machine Learning</i>, vol. 114, 257.'
---

![Graphical abstract](/images/2025-10-19-bridging-xai-and-spectral-analysis.png)

Understanding the inductive bias of Deep Graph Networks (DGNs) is crucial because it reveals how these models generalize from training data to unseen data. Discovering these learning assumptions, and their alignment to the task’s characteristics, allows informed architectural design choices and facilitates interpretation. With this goal, we analyze the different inductive biases of DGNs by relating the node-level explanations produced by explainable AI (XAI) methods to known network science measures of lower-order (local) and higher-order (increasingly global) connectivity. We then apply graph signal processing to refine this analysis at the granularity of the graph frequency spectrum spanned by the explanation signals. Our main finding is that different DGNs focus on different regions of the graph frequency spectrum, and in particular, high-frequency DGNs generalize by focusing on lower-order graph connectivity, while low-frequency DGNs generalize by recognizing higher-order graph structures. This characterization is first derived on synthetic benchmarks by showing that explanations align with network science measures sitting at the two extremes of the spectrum (Katz centrality in the high frequencies, and Fiedler eigenvector scores in the low frequencies). Moving to real-world chemical benchmarks, this result is generalized by showing that inductive biases do indeed lie on a continuum that corresponds to sub-regions of the frequency spectrum.