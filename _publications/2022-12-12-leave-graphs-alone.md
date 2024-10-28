---
title: "Leave Graphs Alone: Addressing Over-Squashing without Rewiring"
collection: publications
category: conferences
permalink: /publication/2022-12-12-leave-graphs-alone
excerpt: 'GESN achieves a significantly better accuracy on six heterophilic node classification tasks via tuning Lipschitz constants instead of resorting to graph rewiring.'
date: 2022-12-12
venue: 'LoG'
paperurl: 'https://openreview.net/forum?id=vEbUaN9Z2V8'
citation: 'D. Tortorella, A. Micheli (2022). &quot;Leave Graphs Alone: Addressing Over-Squashing without Rewiring&quot; (Extended Abstract). <i>Presented at the First Learning on Graphs Conference (LoG 2022)</i>, Virtual Event, December 9–12, 2022.'
---

![Graphical abstract](/images/2022-12-12-leave-graphs-alone.png)

Recent works have investigated the role of graph bottlenecks in preventing long-range information propagation in message-passing graph neural networks, causing the so-called 'over-squashing' phenomenon. As a remedy, graph rewiring mechanisms have been proposed as preprocessing steps. Graph Echo State Networks (GESNs) are a reservoir computing model for graphs, where node embeddings are recursively computed by an untrained message-passing function. In this paper, we show that GESNs can achieve a significantly better accuracy on six heterophilic node classification tasks without altering the graph connectivity, thus suggesting a different route for addressing the over-squashing problem.