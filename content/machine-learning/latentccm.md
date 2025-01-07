---
title: "Latent Convergent Cross Mapping : Causal Directions between Irregular Time Series"
date: 2022-01-26T15:31:13+01:00
draft: false
categories: machine-learning
description: "How to infer causal direction between irregularly sampled time series."
keywords: "causality, time series, discovery"
---

Discovering causal structures of temporal processes is a major tool of scientific inquiry because it helps us better understand and explain the mechanisms driving a phenomenon of interest, thereby facilitating analysis, reasoning, and synthesis for such systems. However, accurately inferring causal structures within a phenomenon based on observational data only is still an open problem. Indeed, this type of data usually consists in short time series with missing or noisy values for which causal inference is increasingly difficult. In this work, we propose a method to uncover causal relations in chaotic dynamical systems from short, noisy and sporadic time series (that is, incomplete observations at infrequent and irregular intervals) where the classical convergent cross mapping (CCM) fails. Our method works by learning a Neural ODE latent process modeling the state-space dynamics of the time series and by checking the existence of a continuous map between the resulting processes. We provide theoretical analysis and show empirically that Latent-CCM can reliably uncover the true causal pattern, unlike traditional methods

Read our paper [here](https://openreview.net/pdf?id=4TSiOTkKe5P)

(Presented at ICLR 2021)
