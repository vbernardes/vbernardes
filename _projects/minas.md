---
title: "Novelty Detection with MINAS"
excerpt: "Python implementation of the MINAS multi-class novelty detection algorithm for data streams."
header:
  teaser: /assets/images/minas_viz_sample.png
---

{% include figure image_path="/assets/images/minas_viz.png" alt="MINAS Clusters" caption="Clusters identified for different classes in stream." %}

This project is a Python implementation of the MINAS multi-class novelty detection algorithm for data streams. The implementation supports `scikit-multiflow`.
The algorithm uses clustering techniques and has features for detecting novelties, concept extension, concept drift, and forgetting outdated stream states.
In initial tests with the [Kaggle credit card fraud detection data set](https://www.kaggle.com/mlg-ulb/creditcardfraud), using prequential evaluation, the model achieved 82.7% recall for fraud examples. 

Please check out more details and a quick-start guide on the [project page](https://github.com/vbernardes/minas).
