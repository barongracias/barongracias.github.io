---
title: "InterPyApp - 5D->1D interpolation platform"
permalink: /projects/interpyapp/
layout: single
author_profile: true
---

Full-stack app for uploading multi-dimensional datasets, running interpolations with multiple backends, and exposing results via an API and UI.

## What I built
- FastAPI backend serving interpolation endpoints with NumPy and TensorFlow backends for quick tests vs accelerated runs.
- Next.js frontend to upload CSVs, configure model parameters, and visualise 5D->1D predictions with charts and tables.
- Artifact tracking for runs (config + outputs) so experiments are reproducible and comparable.
- Docker/local scripts to spin up the full stack consistently and seed synthetic data for demos.

## Problem
Researchers needed an easy way to test interpolation approaches across high-dimensional datasets without wiring up separate scripts, APIs, and UIs each time.

## Approach
1) Defined a common schema for uploaded datasets and validation to catch bad rows early.  
2) Implemented interchangeable compute backends (NumPy for baselines, TensorFlow for heavier fits) behind a single API contract.  
3) Built UI flows for uploading data, selecting backends/hyperparameters, running jobs, and browsing artifacts.  
4) Added synthetic data generators and fixtures to demo the system and make regression testing easy.  
5) Containerised the stack with Docker Compose and provided local scripts so collaborators can run it with minimal setup.

## Impact
- Faster iteration: switch backends and configs without rewriting code.  
- Reproducibility: each run stores inputs, configs, and outputs for side-by-side comparison.  
- Shareable demos: synthetic datasets and containers let others trial the tool without touching live data.

## Stack
FastAPI, Python (NumPy, TensorFlow), Next.js/React, Docker Compose, GitHub Actions for lint/tests.

<a class="btn btn--primary" href="https://github.com/barongracias/InterPyApp">View repo</a>
