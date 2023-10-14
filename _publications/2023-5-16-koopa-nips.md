---
title: "Koopa: Learning Non-stationary Time Series Dynamics with Koopman Predictors"
collection: publications
permalink: /publications/2023-5-16-koopa-nips
excerpt: 'Real-world time series is characterized by intrinsic non-stationarity that poses a principal challenge for deep forecasting models. While previous models suffer from complicated series variations induced by changing temporal distribution, we tackle non-stationary time series with modern Koopman theory that fundamentally considers the underlying time-variant dynamics. Inspired by Koopman theory of portraying complex dynamical systems, we disentangle time-variant and time-invariant components from intricate non-stationary series by Fourier Filter and design Koopman Predictor to advance respective dynamics forward. Technically, we propose Koopa as a novel Koopman forecaster composed of stackable blocks that learn hierarchical dynamics. Koopa seeks measurement functions for Koopman embedding and utilizes Koopman operators as linear portraits of implicit transition. To cope with time-variant dynamics that exhibits strong locality, Koopa calculates context-aware operators in the temporal neighborhood and is able to utilize incoming ground truth to scale up forecast horizon. Besides, by integrating Koopman Predictors into deep residual structure, we ravel out the binding reconstruction loss in previous Koopman forecasters and achieve end-to-end forecasting objective optimization. Compared with the state-of-the-art model, Koopa achieves competitive performance while saving **77.3%** training time and **76.0%** memory.'
date: 2023-05-16
venue: 'NeurIPS'
paperurl: 'https://arxiv.org/abs/2305.18803'
citation: 'Liu, Y, Li, C, Wang, J., & Long, M. (2023). Koopa: Learning Non-stationary Time Series Dynamics with Koopman Predictors[J]. NeurIPS 2023.'
---


[Download paper here](https://arxiv.org/pdf/2305.18803.pdf)
