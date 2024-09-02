---
title: "Top-Ambiguity Samples Matter: Understanding Why Deep Ensemble Works in Selective Classification"
collection: publications
permalink: /publication/2023-10-07-NeurIPS
excerpt: 'We prove that, under some assumptions, ensemble model outperforms its members on a range of coverage for selective classification.'
date: 2023-10-07
venue: 'NeurIPS'
paperurl: 'https://openreview.net/forum?id=WBq6Q4ml04'
citation: 'Qiang Ding, Yixuan Cao, and Ping Luo. Top-Ambiguity Samples Matter: Understanding Why Deep Ensemble Works in Selective Classification. In NeurIPS, 2023.'
---

Selective classification allows a machine learning model to reject some hard inputs and thus improve the reliability of its predictions. In this area, the ensemble method is powerful in practice, but there has been no solid analysis on why the ensemble method works. 

Inspired by an interesting empirical result that the improvement of the ensemble largely comes from top-ambiguity samples where its member models diverge, we prove that, based on some assumptions, the ensemble has a lower selective risk than the member model for any coverage within a range. The proof is nontrivial since the selective risk is a non-convex function of the model prediction. The assumptions and the theoretical results are supported by systematic experiments on both computer vision and natural language processing tasks.

![An illustration of the intuition of our analysis.](/images/ensemble-selective-classification.png)

[paper](https://openreview.net/forum?id=WBq6Q4ml04)
