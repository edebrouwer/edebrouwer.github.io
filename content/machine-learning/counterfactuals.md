---
title: "Deep Counterfactual Estimation with Categorical Background Variables"
date: 2023-11-21T09:52:10-05:00
draft: false
categories: machine-learning
description: "Answering the what if question with counterfactuals"
keywords: "causality, counterfacutals, "
---

Referred to as the third rung of the causal inference ladder, counterfactual queries typically ask the" What if?" question retrospectively. The standard approach to estimate counterfactuals resides in using a structural equation model that accurately reflects the underlying data generating process. However, such models are seldom available in practice and one usually wishes to infer them from observational data alone. Unfortunately, the correct structural equation model is in general not identifiable from the observed factual distribution. Nevertheless, in this work, we show that under the assumption that the main latent contributors to the treatment responses are categorical, the counterfactuals can be still reliably predicted. Building upon this assumption, we introduce CounterFactual Query Prediction (CFQP), a novel method to infer counterfactuals from continuous observations when the background variables are categorical. We show that our method significantly outperforms previously available deep-learning-based counterfactual methods, both theoretically and empirically on time series and image data. Our code is available at https://github.com/edebrouwer/cfqp.

Read our paper [here](https://proceedings.neurips.cc/paper_files/paper/2022/file/e4a0d8aef3567f742b0794844d9b5847-Paper-Conference.pdf)

(Presented at NeurIPS 2022)