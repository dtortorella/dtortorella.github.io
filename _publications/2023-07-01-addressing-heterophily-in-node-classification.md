---
title: "Addressing Heterophily in Node Classification with Graph Echo State Networks"
collection: publications
category: journals
permalink: /publication/2023-07-01-addressing-heterophily-in-node-classification
excerpt: 'Node-level GESN is highly effective for heterophilic node classification tasks, while also being efficient and resilient to over-smoothing.'
date: 2023-07-01
venue: 'Neurocomputing'
paperurl: 'https://doi.org/10.1016/j.neucom.2023.126506'
citation: 'A. Micheli, D. Tortorella (2023). &quot;Addressing Heterophily in Node Classification with Graph Echo State Networks.&quot; <i>Neurocomputing</i>, vol. 550, 126506.'
---

![Graphical abstract](/images/2023-07-01-addressing-heterophily-in-node-classification.jpg)

Node classification tasks on graphs are addressed via fully-trained deep message-passing models that learn a hierarchy of node representations via multiple aggregations of a node's neighbourhood. While effective on graphs that exhibit a high ratio of intra-class edges, this approach poses challenges in the opposite case, i.e. heterophily, where nodes belonging to the same class are usually further apart. In graphs with a high degree of heterophily, the smoothed representations based on close neighbours computed by convolutional models are no longer effective. So far, architectural variations in message-passing models to reduce excessive smoothing or rewiring the input graph to improve longer-range message passing have been proposed. In this paper, we address the challenges of heterophilic graphs with Graph Echo State Network (GESN) for node classification. GESN is a reservoir computing model for graphs, where node embeddings are recursively computed by an untrained message-passing function. Our experiments show that reservoir models are able to achieve better or comparable accuracy with respect to most fully trained deep models that implement ad hoc variations in the architectural bias or perform rewiring as a preprocessing step on the input graph, with an improvement in terms of efficiency/accuracy trade-off. Furthermore, our analysis shows that GESN is able to effectively encode the structural relationships of a graph node, by showing a correlation between iterations of the recursive embedding function and the distribution of shortest paths in a graph.