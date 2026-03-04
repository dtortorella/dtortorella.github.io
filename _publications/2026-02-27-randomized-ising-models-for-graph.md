---
title: "Randomized Ising models for graph node representation"
collection: publications
category: journals
permalink: /publication/2026-02-27-randomized-ising-models-for-graph
excerpt: 'RIM4G is a new model for graph node representation that is ameanable to physical implementation on non-conventional hardware.'
date: 2026-02-27
venue: 'Neurocomputing'
paperurl: 'https://doi.org/10.1016/j.neucom.2026.133195'
citation: 'M.G. Berni, A. Brau, A. Micheli, D. Tortorella (2026). &quot;Randomized Ising models for graph node representation.&quot; <i>Neurocomputing</i>, vol. 679, 133195.'
---

![Graphical abstract](/images/2026-02-27-randomized-ising-models-for-graph.png)

The increasing scale and complexity of graph-structured data in domains such as citation networks, social media, and e-commerce have exposed the computational limits of conventional graph learning models such as Graph Neural Networks (GNNs) and Graph Transformers (GTs). Reservoir computing (RC) offers a promising alternative by decoupling training complexity from model expressiveness, as demonstrated by Graph Echo State Networks (GESNs). However, traditional RC implementations on von Neumann architectures face bottlenecks due to the separation of memory and data processing. Emerging neuromorphic platforms — such as FPGAs, spintronics, and memristors — offer low-power, high-throughput alternatives for scalable graph learning. In this work, we introduce Randomized Ising Models for Graphs (RIM4G), a reservoir-based framework that encodes node representations via spin dynamics governed by the Lenz–Ising model. RIM4G integrates graph topology and input features through spin couplings and external magnetic fields, respectively, and is simulated using Metropolis sampling with theoretical guarantees on convergence. Evaluated on seven benchmark node classification tasks, RIM4G achieves accuracy comparable to GESNs and with fully-trained GNNs and GTs. Our analysis highlights RIM4G’s robustness to thermal noise and its preference for sparse reservoir matrices, suggesting its suitability for future deployment on unconventional hardware.