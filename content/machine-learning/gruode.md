---
title: "Continuous modeling of sporadically-observed time series"
date: 2022-01-25T15:31:13+01:00
draft: false
categories: machine-learning
---

Modeling real-world multidimensional time series can be particularly challenging when these are sporadically observed (ie, sampling is irregular both in time and across dimensions)—such as in the case of clinical patient data. To address these challenges, we propose (1) a continuous-time version of the Gated Recurrent Unit, building upon the recent Neural Ordinary Differential Equations (Chen et al., 2018), and (2) a Bayesian update network that processes the sporadic observations. We bring these two ideas together in our GRU-ODE-Bayes method. We then demonstrate that the proposed method encodes a continuity prior for the latent process and that it can exactly represent the Fokker-Planck dynamics of complex processes driven by a multidimensional stochastic differential equation. Additionally, empirical evaluation shows that our method outperforms the state of the art on both synthetic data and real-world data with applications in healthcare and climate forecast. What is more, the continuity prior is shown to be well suited for low number of samples settings.

Read the whole paper [here](https://proceedings.neurips.cc/paper/2019/file/455cb2657aaa59e32fad80cb0b65b9dc-Paper.pdf)

(Poster at NeurIPS 2019)
