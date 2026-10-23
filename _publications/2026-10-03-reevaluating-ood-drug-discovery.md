---
title: "Re-evaluating Out-of-Distribution Learning in Drug Discovery"
collection: publications
category: conferences
permalink: /publication/2026-10-03-reevaluating-ood-drug-discovery
excerpt: 'We re-evaluate out-of-distribution generalization in drug discovery (hit identification) learning tasks.'
date: 2026-10-03
venue: 'AIxIA'
paperurl: 'https://doi.org/10.1007/978-3-032-40774-0_11'
citation: 'F. Capria, A. Micheli, D. Tortorella (2027). &quot;Re-evaluating Out-of-Distribution Learning in Drug Discovery.&quot; <i>AIxIA 2026 – Advances in Artificial Intelligence. AIxIA 2026</i>, LNCS vol. 17131, pp. 143-154.'
---

![Graphical abstract](/images/2026-10-03-reevaluating-ood-drug-discovery.png)

Tanimoto similarity is widely used to define chemical novelty and out-of-distribution (OOD) learning regimes in drug discovery, yet it fails to capture the underlying mechanisms of dataset shift. In this work, we apply explainability techniques on machine learning models to investigate the nature of distribution shifts across training, validation, and test sets. Our analysis reveals that OOD scenarios arise from distinct sources, including class-prior shift, covariate shift in molecular fingerprints, and concept shift in the input-target relationship—factors not reflected by purely similarity-based metrics. By leveraging model explanations, we show that splits constructed using Tanimoto thresholds are insufficient to characterize the type of shift present at test time. This explains why OOD validation, as often currently implemented, does not lead to improved OOD generalization in practice. Our findings highlight the importance of diagnosing shift types using interpretable methods and suggest that robustness can only be achieved by developing and applying strategies tailored to the specific nature of the dataset shift.
