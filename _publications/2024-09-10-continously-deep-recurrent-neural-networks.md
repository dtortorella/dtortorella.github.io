---
title: "Continuously Deep Recurrent Neural Networks"
collection: publications
category: conferences
permalink: /publication/2024-09-10-continously-deep-recurrent-neural-networks
excerpt: 'A continuous-depth ESN is proposed, where a smooth depth hyperparameter regulates the extent of local connections.'
date: 2024-09-10
venue: 'ECML PKDD'
paperurl: 'https://doi.org/10.1007/978-3-031-70368-3_4'
citation: 'A. Ceni, P. F. Dominey, C. Gallicchio, A. Micheli, L. Pedrelli, D. Tortorella (2024). &quot;Continuously Deep Recurrent Neural Networks.&quot; <i>Machine Learning and Knowledge Discovery in Databases: Research Track. ECML PKDD 2024.</i> LNCS vol. 14947, pp. 59-73.'
---

![Graphical abstract](/images/2024-09-10-continously-deep-recurrent-neural-networks.png)

The architecture of multi-layer dynamic neural systems traditionally contains recurrent neurons organized in successive well-defined layers. In this paper, we introduce a new class of recurrent neural models based on a fundamentally different type of topological organization than the conventionally used deep recurrent networks, and directly inspired by the way cortical networks in the brain process information at multiple temporal scales. We explore the novel paradigm from the perspective of Reservoir Computing (RC), a popular approach to designing efficiently trainable recurrent neural networks, and introduce the Continuously-Deep Echo State Network (C-DESN). The proposed C-DESN architecture comprises a reservoir layer of untrained recurrent neurons connected in a biologically inspired exponentially decaying pattern based on distance. The depth of the resulting neural information processing system is modulated by a single depth hyperparameter that controls the extent of local connectivity. Mathematically, we analyze the dynamical stability properties of the continuously deep reservoir, providing a rigorous bound on the resulting eigenspectrum. Empirically, we show that the novel recurrent architecture is biased toward tunable temporal resolution processing in the same way as conventional deep recurrent neural networks. Additionally, our experiments on short-term memory capacity and real-world time-series reconstruction demonstrate how the depth hyperparameter of C-DESN can effectively regulate the temporal scale in the reservoir's dynamic behavior.