---
title: "Topological Graph Neural Networks"
date: 2022-01-27T15:31:13+01:00
draft: false
categories: machine-learning
---

Graph neural networks (GNNs) are a powerful architecture for tackling graph learning tasks, yet have been shown to be oblivious to eminent substructures such as cycles. We present TOGL, a novel layer that incorporates global topological information of a graph using persistent homology. TOGL can be easily integrated into any type of GNN and is strictly more expressive in terms of the Weisfeiler-Lehman graph isomorphism test. Augmenting GNNs with our layer leads to improved predictive performance for graph and node classification tasks, both on synthetic data sets (which can be classified by humans using their topology but not by ordinary GNNs) and on real-world data.

Read our paper [here](https://arxiv.org/abs/2102.07835)

(Poster at ICLR 2022)
