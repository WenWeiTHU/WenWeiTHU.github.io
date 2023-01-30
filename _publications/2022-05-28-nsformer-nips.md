---
title: "Non-stationary Transformers: Rethinking the Stationarity in Time Series Forecasting"
collection: publications
permalink: /publications/2022-05-28-nsformer-arxiv
excerpt: 'Transformers have shown great power in time series forecasting due to their global-range modeling ability. However, their performance can degenerate terribly on non-stationary real-world data in which the joint distribution changes over time. Previous studies primarily adopt stationarization to reduce the non-stationarity of original series for better predictability. But the stationarized series deprived of inherent non-stationarity can be less instructive for real-world bursty events forecasting. This problem, termed over-stationarization in this paper, leads Transformers to generate indistinguishable temporal attentions for different series and impedes the predictive capability of deep models. To tackle the dilemma between series predictability and model capability, we propose Non-stationary Transformers as a generic framework with two interdependent modules: Series Stationarization and De-stationary Attention. Concretely, Series Stationarization unifies the statistics of each input and converts the output with restored statistics for better predictability. To address over-stationarization, De-stationary Attention is devised to recover the intrinsic non-stationary information into temporal dependencies by approximating distinguishable attentions learned from unstationarized series. Our Non-stationary Transformers framework consistently boosts mainstream Transformers by a large margin, which reduces 49.43% MSE on Transformer, 47.34% on Informer, and 46.89% on Reformer, making them the state-of-the-art in time series forecasting.'
date: 2022-05-28
venue: 'NeurIPS'
paperurl: 'https://arxiv.org/abs/2205.14415'
citation: '**Liu, Y.**, Wu, H., Wang, J., & Long, M. (2022). Non-stationary Transformers: Rethinking the Stationarity in Time Series Forecasting. NeurIPS 2022.'
---

[Download paper here](https://arxiv.org/pdf/2205.14415.pdf)

