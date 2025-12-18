---
title: "Business vs Personal Account Classifier"
permalink: /projects/account-classifier/
layout: single
author_profile: true
---

An end-to-end classification system that labels bank accounts as business or personal to unlock better segmentation, risk models, and analytics at scale.

## What I built
- Production-grade XGBoost model scoring 15m accounts per month with 85%+ accuracy.
- Parallelised data pipelines capable of processing billions of FPS/Bacs/ICS transactions without blowing SLAs.
- Evaluation suite with drift checks, calibration monitoring, and explainability slices for stakeholders.

## Problem
Customer segmentation was noisy and manual, limiting downstream fraud models and reporting. The team needed a consistent, automated classifier that could run monthly at national scale.

## Approach
1) Profiled raw payment features to identify stable signals across schemes.  
2) Engineered sparse categorical and frequency-based features, balancing recall for rare entities with precision for high-volume senders.  
3) Tuned XGBoost with stratified cross-validation and cost-sensitive loss to avoid over-penalising minority classes.  
4) Parallelised execution plans and IO to keep wall-clock times predictable over billions of rows.  
5) Added monitoring on feature drift and business/personal ratio shifts to catch upstream changes early.

## Impact
- Reliable segmentation that improved downstream analytics quality and risk modelling inputs.  
- Clearer reporting for leadership and partners, backed by explainable model outputs.  
- Operational runbooks that made reprocessing routine instead of heroic.

## Stack
Python, XGBoost, pandas, Spark, SQL (Oracle, SSMS, Teradata), Git, Docker, CI/CD.
