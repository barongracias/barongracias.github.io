---
title: "Projects"
permalink: /projects/
layout: single
author_profile: true
---

I build data products that hold up in the messy parts of payments and analytics - long-tail merchants, noisy references, and stakeholders who need signal fast. Here's a mix of open builds and enterprise work.

## Product & data builds
<div class="card-grid three-col">
  <div class="card highlight">
    <p class="eyebrow">Maps + ML</p>
    <h3>g-maps-timeline</h3>
    <p>Fog-of-war travel map that ingests Google Timeline exports, aggregates to H3 grids, and renders MapLibre tiles per year with privacy-first filtering.</p>
    <p class="muted"><a href="https://github.com/barongracias/g-maps-timeline">github.com/barongracias/g-maps-timeline</a></p>
  </div>
  <div class="card">
    <p class="eyebrow">FinTech</p>
    <h3>SFE repayment simulator</h3>
    <p>Next.js app modelling Student Finance England plans (1/2/5 + PGL) with salary timelines, interest assumptions, sensitivity bands, and exports.</p>
    <p class="muted"><a href="https://github.com/barongracias/sfe-repayment-calculator">github.com/barongracias/sfe-repayment-calculator</a></p>
  </div>
  <div class="card">
    <p class="eyebrow">Media + PWA</p>
    <h3>Wednesday's</h3>
    <p>Browser-first MVP that rotates a weekly host, records/plays short clips with MediaRecorder, and supports mock uploads, backups, and PWA install.</p>
    <p class="muted"><a href="https://github.com/barongracias/wednesday-video">github.com/barongracias/wednesday-video</a></p>
  </div>
  <div class="card">
    <p class="eyebrow">AI product checklist</p>
    <h3>Ringers</h3>
    <p>Mock-to-prod blueprint for a sports meetup marketplace: API contract, auth roles, RLS, signed uploads, realtime messaging, and moderation plan.</p>
    <p class="muted"><a href="https://github.com/barongracias/ringers">github.com/barongracias/ringers</a></p>
  </div>
  <div class="card">
    <p class="eyebrow">ML pipeline</p>
    <h3>StockPredict</h3>
    <p>Stock forecasting sandbox with Yahoo Finance ingest, baselines vs tuned models (Lasso, LGBM, XGBoost, RF), grid search, and CLI controls.</p>
    <p class="muted"><a href="https://github.com/barongracias/StockPredict">github.com/barongracias/StockPredict</a></p>
  </div>
  <div class="card">
    <p class="eyebrow">Micro-interaction</p>
    <h3>Kick Up Counter</h3>
    <p>Vite + React mini-game with rate-limited inputs, animated ball physics, and high-score persistence - a small, playful UX tuned for mobile.</p>
    <p class="muted"><a href="https://github.com/barongracias/kickup-counter">github.com/barongracias/kickup-counter</a></p>
  </div>
</div>

## Enterprise impact
- **Payment flows with the UK Office for National Statistics** - published industry-to-industry payment flow insights to forecast economic shocks and UK supply chain shifts.  
- **Business vs personal account classifier** - XGBoost model for 15m+ accounts/month with pipelines tuned for billions of FPS/Bacs/ICS transactions.  
- **Fraud data provider PoV** - PCA/cluster analysis on feature vectors to measure similarity, lift, and early detection value for fraud signals.  
- **Open Banking "payment wrapped"** - categorisation + insights module delivering >80% satisfaction in A/B tests.  
- **Pay.UK NLP and reference hygiene** - tokenised fuzzy matching to Companies House with 88% accuracy across 50m accounts; sentiment/profanity detection on payment references.  
- **Operational intelligence** - exec "60-second" DOMO dashboard cutting crisis response by 75%; resource tool with 99.6% allocation accuracy correcting GBP 3m/year.
- **Multi-team delivery** - reshaped the grad scheme into 1x9 + 2x4.5 month rotations across International Payment Strategy/Portfolio/Project Management, Open Banking, UK Faster Payments, Financial Crime, and the Mastercard Economics Institute.

## Cambridge coursework highlights
- **Particle detector calibration and uncertainty analysis** - estimated detector response parameters from beam energy samples using weighted regression, per-bin and simultaneous likelihood fits, and parametric/non-parametric bootstraps; delivered visualisations and confidence bands (NumPy/pandas/matplotlib, SciPy optimisation).  
- **5D interpolation platform (FastAPI + Next.js)** - full-stack app for 5D to 1D regression with NumPy and TensorFlow backends, file uploads, artifact tracking, and Sphinx docs; scripts for Docker and local dev, plus shared synthetic data packages.  
- **Handwritten digit ML suite with triplet embeddings** - Optuna-tuned MLP classifier with determinism checks, MNIST transfer study, custom triplet loss, and a 2D CIFAR-10 embedding compared against t-SNE; TensorFlow, Optuna, calibration and evaluation tooling.

## Academic & research interests
- **MPhil Machine Learning & AI with Physics, Cambridge** - deep learning, HPC, medical imaging; research on CNN-based satellite trail removal for astronomy.  
- **University of Bath** - physics coursework spanning exoplanet analysis notebooks, numerical methods in C/MATLAB/Python, and instrumentation lab reports.

[Want details or a walk-through? Email me.](mailto:barongracias@gmail.com){: .btn .btn--primary }
