---
title: "An Empirical Evaluation of Rewiring Approaches in Graph Neural Networks"
collection: publications
category: journals
permalink: /publication/2025-06-12-empirical-evaluation-rewiring
excerpt: 'We propse an evaluation framework for graph rewiring methods based on training-free GNNs. In our fair conditions, rewiring rarely improves message-passing on 12 node and graph classification tasks.'
date: 2025-06-12
venue: 'Pattern Recognition Letters'
paperurl: 'https://doi.org/10.1016/j.patrec.2025.05.021'
citation: 'A. Micheli, D. Tortorella (2025). &quot;An Empirical Evaluation of Rewiring Approaches in Graph Neural Networks.&quot; <i>Pattern Recognition Letters</i>, vol. 196, pp. 134–141.'
---

![Graphical abstract](/images/2025-06-12-empirical-evaluation-rewiring.jpg)

Graph neural networks compute node representations by performing multiple message-passing steps that consist in local aggregations of node features. Having deep models that can leverage longer-range interactions between nodes is hindered by the issues of over-smoothing and over-squashing. In particular, the latter is attributed to the graph topology which guides the message-passing, causing a node representation to become insensitive to information contained at distant nodes. Many graph rewiring methods have been proposed to remedy or mitigate this problem. However, properly evaluating the benefits of these methods is made difficult by the coupling of over-squashing with other issues strictly related to model training, such as vanishing gradients. Therefore, we propose an evaluation setting based on message-passing models that do not require training to compute node and graph representations. We perform a systematic experimental comparison on real-world node and graph classification tasks, showing that rewiring the underlying graph rarely does confer a practical benefit for message-passing.