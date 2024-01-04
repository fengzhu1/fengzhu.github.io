---
title: "AntTune: An Efficient Distributed Hyperparameter Optimization System for Large-Scale Data"
collection: publications
permalink: /publication/2023-DASFAA
excerpt: ''
venue: DASFAA
date: 2023-04-14
paperurl: 'https://link.springer.com/chapter/10.1007/978-3-031-30678-5_35'
---

Selecting the best hyperparameter configuration is crucial for the performance of machine learning models over large-scale data. To this end, the automation of hyperparameter optimization (HPO) has been widely applied in many automated machine learning (AutoML) frameworks. However, without the effective mechanisms of early stopping and prior knowledge leveraging, such automation is often time-consuming and even inefficient. To improve efficiency, we introduce AntTune, a distributed HPO system that includes parallel optimization, distributed evaluation, tensor cache, etc. Specifically, in AntTune, a time-saving and lightweight mechanism of early stopping is designed to process multiple trials simultaneously. Also, a tree-based meta-learning approach is developed to leverage knowledge from prior tasks and thus it can speed up current HPO tasks. The extensive experiments on both public and industrial …
[Download paper here](https://link.springer.com/chapter/10.1007/978-3-031-30678-5_35)
