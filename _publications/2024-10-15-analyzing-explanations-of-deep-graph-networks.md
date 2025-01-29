---
title: "Analyzing Explanations of Deep Graph Networks through Node Centrality and Connectivity"
collection: publications
category: conferences
permalink: /publication/2024-10-15-analyzing-explanations-of-deep-graph-networks
excerpt: "We analyze the alignment of DGNs explanations to node centrality and graph connectivity, highlighting the presence of different inductive biases."
date: 2024-10-15
venue: 'Discovery Science'
paperurl: 'https://doi.org/10.1007/978-3-031-78977-9_19'
citation: 'M. Fontanesi, A. Micheli, M. Podda, D. Tortorella (2025). &quot;Analyzing Explanations of Deep Graph Networks through Node Centrality and Connectivity.&quot; <i>Proceedings of the 27th International Conference on Discovery Science (DS 2024)</i>, LNCS vol. 15243, pp. 295-309.'
---

![Graphical abstract](/images/2024-10-15-analyzing-explanations-of-deep-graph-networks.png)

Explanations at the node level produced for Deep Graph Networks (DGNs), i.e. neural networks for graph learning, are commonly used to investigate the relationships between the input graphs and their associated predictions. However, they can also provide relevant information concerning the underlying architecture trained to solve the inductive task. In this work, we analyze explanations generated for convolutional and recursive DGN architectures through the notion of node centrality and graph connectivity as means to gain novel insights on the inductive biases distinguishing these architectural classes of neural networks. We adopt Explainable AI (XAI) to perform model inspection and we compare the retrieved explanations with node centrality and graph connectivity to identify the class assignment policy learned by each model to solve multiple XAI graph classification tasks. Our experimental results indicate that the inductive bias of convolutional DGNs tends towards recognizing high-order graph structures, while the inductive bias of recursive and contractive DGNs tends towards recognizing low-order graph structures.