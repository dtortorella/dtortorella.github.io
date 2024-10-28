---
title: "Discrete-Time Dynamic Graph Echo State Networks"
collection: publications
category: journals
permalink: /publication/2022-05-13-discrete-time-dynamic-graph-echo-state-networks
excerpt: 'DynGESN is introduced as a novel reservoir computing model for temporal graphs. More efficient then temporal graph kernels and 100x faster than temporal GNNs.'
date: 2022-05-13
venue: 'Neurocomputing'
paperurl: 'https://doi.org/10.1016/j.neucom.2022.05.001'
citation: 'A. Micheli, D. Tortorella (2022). &quot;Discrete-Time Dynamic Graph Echo State Networks.&quot; <i>Neurocomputing</i>, vol. 496, pp. 85-95.'
---

![Graphical abstract](/images/2022-05-13-discrete-time-dynamic-graph-echo-state-networks.jpg)

Relations between entities evolving through discrete time-steps can be represented by discrete-time dynamic graphs. Examples include hourly interactions between social network users or daily infection spreading. In this paper, we present Dynamic Graph Echo State Network (DynGESN), a reservoir computing model for the efficient processing of discrete-time dynamic temporal graphs. We prove a sufficient condition for the echo state property, which ensures that graph embeddings are independent of initial conditions, and we briefly analyze reservoir dynamics. DynGESN is compared against temporal graph kernels (TGKs) on twelve graph classification tasks, and against ten different end-to-end trained temporal graph convolutional networks (TGNs) on four vertex regression tasks, since TGKs are limited to graph-level tasks. Compared to TGKs that need to hold the entire history of vertex interactions, our model provides a vector encoding for the dynamic graph that is updated at each time-step without requiring training. Experiments show that our model achieves accuracy in line with TGKs that have comparable computational complexity, while still offering space and time requirements better suited to scale to large-size data. Moreover, DynGESN overall achieves superior or on par accuracy with respect to TGNs, while improving efficiency by up ten times on inference and training time.