---
title: "Efficient quantification on large-scale networks"
collection: publications
category: journals
permalink: /publication/2025-11-07-efficient-quantification-on-large-scale-networks
excerpt: 'We propose XNQ, an efficient model for network quantification that scales on large networks and is resilient to heterophily.'
date: 2025-11-07
venue: 'Machine Learning'
paperurl: 'https://doi.org/10.1007/s10994-025-06915-w'
citation: 'A. Micheli, A. Moreo, M. Podda, F. Sebastiani, W. Simoni, D. Tortorella (2025). &quot;Efficient quantification on large-scale networks.&quot; <i>Machine Learning</i>, vol. 114, 270.'
---

![Graphical abstract](/images/2025-11-07-efficient-quantification-on-large-scale-networks.png)

Network quantification (NQ) is the problem of estimating the proportions of nodes belonging to each class in subsets of unlabelled graph nodes. When prior probability shift is at play, this task cannot be effectively addressed by first classifying the nodes and then counting the class predictions. In addition, unlike non-relational quantification, NQ demands enhanced flexibility in order to capture a broad range of connectivity patterns, resilience to the challenge of heterophily, and scalability to large networks. In order to meet these stringent requirements, we introduce XNQ, a novel method that synergizes the flexibility and efficiency of the unsupervised node embeddings computed by randomized recursive Graph Neural Networks, with an Expectation-Maximization algorithm that provides a robust quantification-aware adjustment to the output probabilities of a calibrated node classifier. In an extensive evaluation, in which we also validate the design choices underpinning XNQ through comprehensive ablation experiments, we find that XNQ consistently and significantly improves on the best network quantification methods to date, thereby setting the new state of the art for this challenging task. XNQ also provides a training speed-up of up to 10x–100x over other methods based on graph learning.