---
title: "Onion Echo State Networks: A Preliminary Analysis of Dynamics"
collection: publications
category: conferences
permalink: /publication/2024-09-18-onion-echo-state-networks-dynamics
excerpt: 'A preliminary analysis of dynamical properties of Onion ESN, a novel reservoir with groups of units presentig an annular spectrum.'
date: 2024-09-18
venue: 'ICANN'
paperurl: 'https://doi.org/10.1007/978-3-031-72359-9_9'
citation: 'D. Tortorella, A. Micheli (2024). &quot;Onion Echo State Networks: A Preliminary Analysis of Dynamics.&quot; <i>Proceedings of the 33rd International Conference on Artificial Neural Networks (ICANN 2024)</i>, LNCS vol. 15025, pp. 117-128.'
---

![Graphical abstract](/images/2024-09-18-onion-echo-state-networks-dynamics.png)

Echo state networks (ESNs) are a class of recurrent neural networks (RNNs) designed according to the Reservoir Computing (RC) approach, where the dynamical part of the model is initialized and left untrained. The reservoir's topology and spectral properties both play an important role in producing an informative encoding of the input sequence. So far, only Deep ESNs have been able to provide a clear hierarchy of representations by structuring the reservoir in multiple layers, thus encoding the input sequence on different time scales. In this paper, we propose Onion ESNs, whose reservoirs are structured in segregated groups of units, each group corresponding to an annular segment of the whole reservoir spectrum. The experimental analysis of our model confirms that groups of reservoir units provide representations specialized in different dynamical regimes and signal frequencies. The results of this paper can potentially be applied to the adaptive designs of ESNs as well as to the design of fully-trained RNNs.