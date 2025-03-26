---
permalink: /
title: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Domenico Tortorella received the PhD in computer science *cum laude* from the University of Pisa, Italy, in 2024 for his thesis "Efficient Models for Deep Learning on Graphs" under the supervision of prof. Alessio Micheli. Previously he received the BSc in computer engineering from the University of Salerno, Italy, in 2017, and the MSc in computer science from the University of Pisa, Italy, in 2020, both *cum laude*. Currently, he is a post-doc research fellow in the Department of Computer Science at the University of Pisa, working for the Future AI Research ([FAIR](https://fondazione-fair.it/)) project, and he is a member of the Computational Intelligence and Machine Learning research group ([CIML](https://ciml.di.unipi.it/)).

# Research topics
- Machine learning for graphs
- Reservoir computing
- Constructive neural networks

# Upcoming conferences
- Special Session on *Design and Theory of Deep Graph Learning* @ IJCNN 2025 [↪](https://sites.google.com/view/dtdgl-2025)
- 3rd International Workshop on Reservoir Computing @ ICANN 2025 [↪](https://sites.google.com/view/reservoircomputing2025)
- Special Session on *Neural Networks for Graphs and Beyond* (NN4G+) @ ICANN 2025 [↪](https://sites.google.com/view/nn4g2025)

# Recent publications
{% assing latest_pubs = site.publications | reverse}
  <ul>{% for post in latest_pubs limit: 3 %}
    {% include archive-single-cv2.html %}
  {% endfor %}</ul>

# Contact
**Room 385**  
**Department of Computer Science, University of Pisa**  
Largo B. Pontecorvo, 3, 56127 Pisa, Italy
