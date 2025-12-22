---
title: "m1-machine-learning - ML suite with triplet embeddings"
permalink: /projects/m1-machine-learning/
layout: single
author_profile: true
---

Coursework portfolio that combines classic supervised baselines with metric learning: MNIST classifiers, triplet-loss embeddings, and transfer to CIFAR-10 for visualisation.

## What I built
- Optuna-tuned MLP classifier on MNIST with deterministic seeding to keep results repeatable.  
- Custom triplet-loss embedding network to separate classes in latent space; visualised vs t-SNE.  
- Transfer experiments testing robustness on CIFAR-10 embeddings and a 2D projection for comparison.  
- Training scripts with checkpoints, reproducibility flags, and reporting of key metrics.

## Problem
Need a compact but rigorous ML suite for coursework that demonstrates optimisation, metric learning, and transfer, with reproducible experiments and clear visual outputs.

## Approach
1) Established deterministic pipelines (seed control, fixed splits) to make hyperparameter searches comparable.  
2) Ran Optuna sweeps on MLP hyperparameters to reach strong MNIST baselines.  
3) Implemented triplet-loss training with hard/semi-hard mining to improve class separation; evaluated embedding quality with distance-based metrics.  
4) Projected embeddings to 2D and contrasted them with t-SNE visualisations to discuss structure and trade-offs.  
5) Ported the learned representations to CIFAR-10 for a small transfer test, documenting where performance held up or degraded.

## Impact
- Demonstrated metric learning benefits over simple classifiers in a controlled setting.  
- Produced reproducible runs and visuals suitable for write-ups or presentations.  
- Clarified limitations when transferring embeddings beyond the source domain.

## Stack
Python, PyTorch, Optuna, NumPy/pandas, Matplotlib/Seaborn for plots, reproducibility utilities.

<a class="btn btn--primary" href="https://github.com/barongracias/m1-machine-learning">View repo</a>
