---
title: "Designs of Graph Echo State Networks for Node Classification"
collection: publications
category: journals
permalink: /publication/2024-06-12-designs-of-graph-echo-state-networks
excerpt: 'Analysis of dense and sparse reservoir designs for node-level GESN via topology-dependent and topology-agnostic richness measures for node embeddings.'
date: 2024-06-12
venue: 'Neurocomputing'
paperurl: 'https://doi.org/10.1016/j.neucom.2024.127965'
citation: 'A. Micheli, D. Tortorella (2024). &quot;Designs of Graph Echo State Networks for Node Classification.&quot; <i>Neurocomputing</i>, vol. 597, 127965.'
---

![Graphical abstract](/images/2024-06-12-designs-of-graph-echo-state-networks.jpg)

Among the Graph Neural Network (GNN) models that address the task of node classification, Graph Echo State Networks (GESN) have proved particularly effective in addressing the challenge of heterophily, i.e. the presence of a significant fraction of inter-class edges in the learning task graph. The effectiveness of GESN is paired with its efficiency, owing to the reservoir computing paradigm. While previous literature has analyzed the design of reservoirs for sequence ESN and GESN for graph-level tasks, the problem of providing effective designs of reservoirs for node-level GESN is so far largely unexplored. In this paper we analyze the impact of different reservoir designs on node classification accuracy and on the quality of node embeddings computed by GESN, focusing both on dense and sparse reservoir layouts. As measures of embedding richness, we adopt both graph topology-dependent metrics previously employed in the analysis of embedding smoothing, and topology-independent metrics from the areas of information theory and numerical analysis. In particular, we propose the application of entropy measures for quantifying information in node embeddings.