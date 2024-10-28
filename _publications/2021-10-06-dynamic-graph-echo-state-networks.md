---
title: "Dynamic Graph Echo State Networks"
collection: publications
category: conferences
permalink: /publication/2021-10-06-dynamic-graph-echo-state-networks
excerpt: 'Preliminary experiments on temporal graph classification with DynGESN, a novel reservoir computing model for dynamic graphs.'
date: 2021-10-06
venue: 'ESANN'
paperurl: 'https://doi.org/10.14428/esann/2021.ES2021-70'
citation: 'D. Tortorella, A. Micheli (2021). &quot;Dynamic Graph Echo State Networks.&quot; <i>Proceedings of the 29th European Symposium on Artificial Neural Networks, Computational Intelligence and Machine Learning (ESANN 2021)</i>, pp. 99-104.'
---

![Graphical abstract](/images/2021-10-06-dynamic-graph-echo-state-networks.png)

Dynamic temporal graphs represent evolving relations between entities, e.g. interactions between social network users or infection spreading. We propose an extension of graph echo state networks for the efficient processing of dynamic temporal graphs, with a sufficient condition for their echo state property, and an experimental analysis of reservoir layout impact. Compared to temporal graph kernels that need to hold the entire history of vertex interactions, our model provides a vector encoding for the dynamic graph that is updated at each time-step without requiring training. Experiments show accuracy comparable to approximate temporal graph kernels on twelve dissemination process classification tasks.