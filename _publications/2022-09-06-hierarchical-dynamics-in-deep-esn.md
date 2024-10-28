---
title: "Hierarchical Dynamics in Deep Echo State Networks"
collection: publications
category: conferences
permalink: /publication/2022-09-06-hierarchical-dynamics-in-deep-esn
excerpt: 'An in-depth theoretical analysis of asymptotic dynamics in Deep ESNs with different contractivity hierarchies.'
date: 2022-09-06
venue: 'ICANN'
paperurl: 'https://doi.org/10.1007/978-3-031-15934-3_55'
citation: 'D. Tortorella, C. Gallicchio, A. Micheli (2022). &quot;Hierarchical Dynamics in Deep Echo State Networks.&quot; <i>Proceedings of the 31st International Conference on Artificial Neural Networks (ICANN 2022)</i>, pp. 668-679.'
---

![Graphical abstract](/images/2022-09-06-hierarchical-dynamics-in-deep-esn.png)

Reservoir computing (RC) is a popular approach to the efficient design of recurrent neural networks (RNNs), where the dynamical part of the model is initialized and left untrained. Deep echo state networks (ESNs) combined the deep learning approach with RC, by structuring the reservoir in multiple layers, and thus offering the striking advantage of encoding the input sequence on different time-scales. A key factor for the effectiveness of ESNs is the echo state property (ESP), which ensures the asymptotic stability of the reservoir dynamics. In this paper, we perform an in-depth theoretical analysis of asymptotic dynamics in Deep ESNs with different contractivity hierarchies, offering a more accurate sufficient condition of the ESP. We investigate how different hierarchies of contractivity affect memory capacity and predictive performance in regression tasks, concluding that structuring reservoir layers in decreasing contractivity is the best design choice. The results of this paper can potentially be applied also to the design of fully-trained RNNs.