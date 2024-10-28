---
title: "Entropy Based Regularization Improves Performance in the Forward-Forward Algorithm"
collection: publications
category: conferences
permalink: /publication/2023-10-05-entropy-based-regularization-improves-ffa
excerpt: "Adding a representation entropy term into the loss of Hinton's FFA improves accuracy."
date: 2023-10-05
venue: 'ESANN'
paperurl: 'https://doi.org/10.14428/esann/2023.ES2023-79'
citation: 'M. Pardi, D. Tortorella, A. Micheli (2023). &quot;Entropy Based Regularization Improves Performance in the Forward-Forward Algorithm.&quot; <i>Proceedings of the 31st European Symposium on Artificial Neural Networks, Computational Intelligence and Machine Learning (ESANN 2023)</i>, pp. 393-398.'
---

![Graphical abstract](/images/2023-10-05-entropy-based-regularization-improves-ffa.png)

The forward-forward algorithm (FFA) is a recently proposed alternative to end-to-end backpropagation in deep neural networks. FFA builds networks greedily layer by layer, thus being of particular interest in applications where memory and computational constraints are important. In order to boost layers' ability to transfer useful information to subsequent layers, in this paper we propose a novel regularization term for the layer-wise loss function that is based on Renyi's quadratic entropy. Preliminary experiments show accuracy is generally significantly improved across all network architectures. In particular, smaller architectures become more effective in addressing our classification tasks compared to the original FFA.