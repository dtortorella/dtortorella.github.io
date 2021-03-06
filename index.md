---
title: Domenico Tortorella
---

Domenico Tortorella received the BSc in computer engineering from the University of Salerno, Italy, in 2017, and the MSc in computer science from the University of Pisa, Italy, in 2020. Currently, he is a PhD student in computer science at the University of Pisa under the supervision of prof. Alessio Micheli, working within the Computational Intelligence and Machine Learning research group ([CIML](https://ciml.di.unipi.it/)) at the Department of Computer Science.

# Research topics
- Machine learning for graphs
- Reservoir computing
- Constructive neural networks

# Publications
- D. Tortorella, A. Micheli (2022). ***Beyond Homophily with Graph Echo State Networks***. Accepted for oral presentation at ESANN 2022
    > Graph Echo State Networks (GESN) have already demonstrated their efficacy and efficiency in graph classification tasks. However, semi-supervised node classification brought out the problem of over-smoothing in end-to-end trained deep models, which causes a bias towards high homophily graphs. We evaluate for the first time GESN on node classification tasks with different degrees of homophily, analyzing also the impact of the reservoir radius. Our experiments show that reservoir models are able to achieve better or comparable accuracy with respect to fully trained deep models that implement ad hoc variations in the architectural bias, with a gain in terms of efficiency.

- D. Tortorella, C. Gallicchio, A. Micheli (2022). ***Hierarchical Dynamics in Deep Echo State Networks***. Accepted at ICANN 2022
    > Reservoir computing (RC) is a popular approach to the efficient design of recurrent neural networks (RNNs), where the dynamical part of the model is initialized and left untrained. Deep echo state networks (ESNs) combined the deep learning approach with RC, by structuring the reservoir in multiple layers, and thus offering the striking advantage of encoding the input sequence on different time-scales. A key factor for the effectiveness of ESNs is the echo state property (ESP), which ensures the asymptotic stability of the reservoir dynamics. In this paper, we perform an in-depth theoretical analysis of asymptotic dynamics in Deep ESNs with different contractivity hierarchies, offering a more accurate sufficient condition of the ESP. We investigate how different hierarchies of contractivity affect memory capacity and predictive performance in regression tasks, concluding that structuring reservoir layers in decreasing contractivity is the best design choice. The results of this paper can potentially be applied also to the design of fully-trained RNNs.

- D. Tortorella, C. Gallicchio, A. Micheli (2022). ***Spectral Bounds for Graph Echo State Network Stability***. The 2022 International Joint Conference on Neural Networks (accepted for oral presentation)
    > Graph echo state networks (GESN) are a class of reservoir computing models for the efficient and effective processing of graphs. They compute graph embeddings by the convergence to a fixed point of a dynamical system, randomly initialized according to a generalization of the echo state property, called the graph embedding stability (GES) property. In this paper, we prove new and more accurate bounds for necessary and sufficient GES conditions.
Experiments demonstrate how these bounds allow an easier parameter selection and better quality reservoirs.

- A. Micheli, D. Tortorella (2022). ***Discrete-Time Dynamic Graph Echo State Networks***. Neurocomputing, vol. 496, pp. 85-95 [doi:10.1016/j.neucom.2022.05.001](https://doi.org/10.1016/j.neucom.2022.05.001)
    > Relations between entities evolving through discrete time-steps can be represented by discrete-time dynamic graphs. Examples include hourly interactions between social network users or daily infection spreading. In this paper, we present Dynamic Graph Echo State Network (DynGESN), a reservoir computing model for the efficient processing of discrete-time dynamic temporal graphs. We prove a sufficient condition for the echo state property, which ensures that graph embeddings are independent of initial conditions, and we briefly analyze reservoir dynamics. DynGESN is compared against temporal graph kernels (TGKs) on twelve graph classification tasks, and against ten different end-to-end trained temporal graph convolutional networks (TGNs) on four vertex regression tasks, since TGKs are limited to graph-level tasks. Compared to TGKs that need to hold the entire history of vertex interactions, our model provides a vector encoding for the dynamic graph that is updated at each time-step without requiring training. Experiments show that our model achieves accuracy in line with TGKs that have comparable computational complexity, while still offering space and time requirements better suited to scale to large-size data. Moreover, DynGESN overall achieves superior or on par accuracy with respect to TGNs, while improving efficiency by up ten times on inference and training time.

- D. Tortorella, A. Micheli (2021). ***Dynamic Graph Echo State Networks***. Proceedings of the 29th European Symposium on Artificial Neural Networks, Computational Intelligence and Machine Learning (ESANN 2021), pp. 99-104 [doi:10.14428/esann/2021.ES2021-70](https://doi.org/10.14428/esann/2021.ES2021-70)
    > Dynamic temporal graphs represent evolving relations between entities, e.g. interactions between social network users or infection spreading. We propose an extension of graph echo state networks for the efficient processing of dynamic temporal graphs, with a sufficient condition for their echo state property, and an experimental analysis of reservoir layout impact. Compared to temporal graph kernels that need to hold the entire history of vertex interactions, our model provides a vector encoding for the dynamic graph that is updated at each time-step without requiring training. Experiments show accuracy comparable to approximate temporal graph kernels on twelve dissemination process classification tasks.

# Contact
**Room 298a**, Department of Computer Science, University of Pisa  
Largo B. Pontecorvo, 3, 56127 Pisa, Italy

![ORCID](https://info.orcid.org/wp-content/uploads/2020/12/orcid_16x16.gif) [ORCID 0000-0003-3910-7713](https://orcid.org/0000-0003-3910-7713)   
[Scopus](https://www.scopus.com/authid/detail.uri?authorId=57313459700)
[Web of Science](https://publons.com/researcher/CAH-3249-2022/)
[Scholar](https://scholar.google.com/citations?user=xfp2G08AAAAJ)
