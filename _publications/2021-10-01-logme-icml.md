---
title: "LogME: Practical Assessment of Pre-trained Models for Transfer Learning"
collection: publications
permalink: /publications/2021-10-01-logme-icml
excerpt: 'This paper studies task adaptive pre-trained model selection, an underexplored problem of assessing pre-trained models for the target task and select best ones from the model zoo **without fine-tuning**. A few pilot works addressed the problem in transferring supervised pre-trained models to classification tasks, but they cannot handle emerging unsupervised pre-trained models or regression tasks. In pursuit of a practical assessment method, we propose to estimate the maximum value of label evidence given features extracted by pre-trained models. Unlike the maximum likelihood, the maximum evidence is **immune to over-fitting**, while its expensive computation can be dramatically reduced by our carefully designed algorithm. The Logarithm of Maximum Evidence (LogME) can be used to assess pre-trained models for transfer learning: a pre-trained model with a high LogME value is likely to have good transfer performance. LogME is **fast, accurate, and general**, characterizing itself as the first practical method for assessing pre-trained models. Compared with brute-force fine-tuning, LogME brings at most 3000× speedup in wall-clock time and requires only 1 memory footprint. It outperforms prior methods by a large margin in their setting and is applicable to new settings. It is general enough for diverse pre-trained models (supervised pre-trained and unsupervised pre-trained), downstream tasks (classification and regression), and modalities (vision and language). Code is available at this [repository](https://github.com/thuml/LogME).'
date: 2021-10-01
venue: 'ICML'
paperurl: 'http://proceedings.mlr.press/v139/you21b.html'
citation: 'You, K., Liu, Y., Wang, J. &amp; Long, M.. (2021). LogME: Practical Assessment of Pre-trained Models for Transfer Learning. ICML 2021.'
---

[Download paper here](http://proceedings.mlr.press/v139/you21b/you21b.pdf)
