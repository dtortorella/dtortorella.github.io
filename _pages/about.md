---
permalink: /
title: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Domenico Tortorella received the PhD in computer science *cum laude* from the University of Pisa, Italy, in 2024 for his thesis "Efficient Models for Deep Learning on Graphs" under the supervision of prof. Alessio Micheli. Previously he received the BSc in computer engineering from the University of Salerno, Italy, in 2017, and the MSc in computer science from the University of Pisa, Italy, in 2020, both *cum laude*. Currently, he is an assistant professor (RTD-A) in the Department of Computer Science at the University of Pisa, and he is a member of the Computational Intelligence and Machine Learning research group ([CIML](https://ciml.di.unipi.it/)). He currently hold the office of Secretary of the European Neural Network Society ([ENNS](https://e-nns.org/current-enns-executive-committee/)).

# Research topics
My research interests include machine learning on structured data, with a particular focus on neural networks for sequences and graphs, reservoir computing, and explainable AI. I have contributed to the development of efficient neural architectures for graphs and the theoretical analysis of their properties, with applications in bioinformatics and cheminformatics.

Read more [here](/research-topics/) about the topics:
- Machine learning for graphs
- Reservoir computing
- Explainable AI

# Upcoming conferences
- 15th IAPR-TC15 International Workshop Graph-Based Representations in Pattern Recognition (GbR 2027) [↪](https://gbrpr.org/)

# Recent publications
{% assign latest_pubs = site.publications | sort: 'date' | reverse %}
  <ul>{% for post in latest_pubs limit: 3 %}
    {% include archive-single-cv2.html %}
  {% endfor %}</ul>

# Contact
**Room 330**  
**Department of Computer Science, University of Pisa**  
Largo B. Pontecorvo, 3, 56127 Pisa, Italy
