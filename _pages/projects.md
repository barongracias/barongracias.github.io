---
title: "Projects"
permalink: /projects/
layout: single
author_profile: true
---

I build data and ML products that stay reliable when data is messy and stakeholders need clear signal. Selected open-source, industry, and academic work that reflects payments-scale delivery and research depth. Looking for how to engage? Visit the [services page](/services/).

## Featured case studies
<div class="card-grid three-col">
  <div class="card highlight">
    <p class="eyebrow">Payments &amp; Fraud</p>
    <h3>Account classifier</h3>
    <p>15m+ accounts/month scored with XGBoost, drift checks, and explainable outputs to feed risk and analytics teams.</p>
    <div class="hero-ctas">
      <a class="btn btn--primary" href="/projects/account-classifier/">Read the case</a>
    </div>
  </div>
  <div class="card">
    <p class="eyebrow">Economic insight</p>
    <h3>Payment flows (ONS)</h3>
    <p>Industry-to-industry flow monitoring for the UK ONS to spot supply chain stress early with reproducible notebooks.</p>
    <div class="hero-ctas">
      <a class="btn" href="/projects/payment-flows-ons/">Read the case</a>
    </div>
  </div>
  <div class="card">
    <p class="eyebrow">Product analytics</p>
    <h3>Payment Wrapped</h3>
    <p>Open Banking categorisation plus Spotify-style insights that delivered 80%+ satisfaction in A/B tests.</p>
    <div class="hero-ctas">
      <a class="btn" href="/projects/payment-wrapped/">Read the case</a>
    </div>
  </div>
</div>

## Open-source case studies
<div class="card-grid two-col">
  <div class="card">
    <p class="eyebrow">Maps + ML</p>
    <h3>g-maps-timeline</h3>
    <p>Fog-of-war travel map built from Google Timeline exports with H3 aggregation and MapLibre tiles.</p>
    <div class="hero-ctas">
      <a class="btn" href="/projects/g-maps-timeline/">Read the case</a>
    </div>
  </div>
  <div class="card">
    <p class="eyebrow">Interpolation platform</p>
    <h3>InterPyApp</h3>
    <p>5D->1D interpolation with FastAPI/Next.js, switchable NumPy/TensorFlow backends, and artifact tracking.</p>
    <div class="hero-ctas">
      <a class="btn" href="/projects/interpyapp/">Read the case</a>
    </div>
  </div>
  <div class="card">
    <p class="eyebrow">FinTech modelling</p>
    <h3>SFE repayment simulator</h3>
    <p>Student Finance England loan modeller with interactive salary timelines, overpayments, and exports.</p>
    <div class="hero-ctas">
      <a class="btn" href="/projects/sfe-repayment/">Read the case</a>
    </div>
  </div>
  <div class="card">
    <p class="eyebrow">Metric learning</p>
    <h3>m1-machine-learning</h3>
    <p>Coursework suite covering MNIST baselines, triplet-loss embeddings, and transfer visualisations.</p>
    <div class="hero-ctas">
      <a class="btn" href="/projects/m1-machine-learning/">Read the case</a>
    </div>
  </div>
</div>

## Git projects (open-source)
- **g-maps-timeline** - fog-of-war travel map that ingests Google Timeline exports, aggregates to H3 grids, and renders MapLibre tiles per year with privacy-first filtering.  
  <span class="muted"><a href="https://github.com/barongracias/FogofWar">github.com/barongracias/FogofWar</a> · <a href="/projects/g-maps-timeline/">Case study</a></span>
- **SFE repayment simulator** - Next.js app modelling Student Finance England plans (1/2/5 + PGL) with salary timelines, interest assumptions, sensitivity bands, and exports.  
  <span class="muted"><a href="https://github.com/barongracias/SFE-Repayment-Calculator">github.com/barongracias/SFE-Repayment-Calculator</a> · <a href="/projects/sfe-repayment/">Case study</a></span>
- **Wednesday's** - browser-first MVP that rotates a weekly host, records/plays short clips with MediaRecorder, and supports mock uploads, backups, and PWA install.  
  <span class="muted"><a href="https://github.com/barongracias/wednesday-video">github.com/barongracias/wednesday-video</a></span>
- **Ringers** - mock-to-prod blueprint for a sports meetup marketplace: API contract, auth roles, RLS, signed uploads, realtime messaging, and moderation plan.  
  <span class="muted"><a href="https://github.com/barongracias/ringers">github.com/barongracias/ringers</a></span>
- **InterPyApp** - FastAPI + Next.js 5D->1D interpolation app with NumPy/TensorFlow backends, file uploads, artifact tracking, and Docker/local scripts.  
  <span class="muted"><a href="https://github.com/barongracias/InterPyApp">github.com/barongracias/InterPyApp</a> · <a href="/projects/interpyapp/">Case study</a></span>
- **StockPredict** - stock forecasting sandbox with Yahoo Finance ingest, baselines vs tuned models (Lasso, LGBM, XGBoost, RF), grid search, and CLI controls.  
  <span class="muted"><a href="https://github.com/barongracias/StockPredict">github.com/barongracias/StockPredict</a></span>
- **Kick Up Counter** - Vite + React mini-game with rate-limited inputs, animated ball physics, and high-score persistence.  
  <span class="muted"><a href="https://github.com/barongracias/kickup-counter">github.com/barongracias/kickup-counter</a></span>

## Industry projects
**Payments & fraud**
- **Payment flows with the UK Office for National Statistics** - published industry-to-industry payment flow insights to forecast economic shocks and UK supply chain shifts. <a href="/projects/payment-flows-ons/">See details</a>.  
- **Business vs personal account classifier** - XGBoost model for 15m+ accounts/month with pipelines tuned for billions of FPS/Bacs/ICS transactions. <a href="/projects/account-classifier/">See details</a>.  
- **Fraud data provider PoV** - PCA/cluster analysis on feature vectors to measure similarity, lift, and early detection value for fraud signals.  
- **Pay.UK NLP and reference hygiene** - tokenised fuzzy matching to Companies House with 88% accuracy across 50m accounts; sentiment/profanity detection on payment references.  
- **Fraud integrations** - integrated with Feedzai; built a Spark adapter to convert input schemas into the AutoML pipeline.  

**Product analytics & experimentation**
- **Open Banking "payment wrapped"** - categorisation + insights module delivering >80% satisfaction in A/B tests. <a href="/projects/payment-wrapped/">See details</a>.  
- **Operational intelligence** - exec "60-second" DOMO dashboard cutting crisis response by 75%; resource tool with 99.6% allocation accuracy correcting GBP 3m/year.  

**Strategy & delivery**
- **Multi-team delivery** - rotations across International Payment Strategy/Portfolio/Project Management, Open Banking, UK Faster Payments, Financial Crime, and the Mastercard Economics Institute to speak both strategy and implementation.  
- **Economics institute** - exploratory analysis on Iceland tourism-driven GDP uplift using OAG flight data to size sector impact.

## Academic projects
- **Cambridge MPhil (ML & AI with Physics)** - research on CNN-based satellite trail removal in astronomical imagery: segmentation models to detect and mask Starlink/OneWeb/other satellite streaks, testing robustness to noise and keeping inference fast for observatories.  
- **Detector calibration & uncertainty analysis** - estimated detector response parameters from beam energy samples using weighted regression, per-bin and simultaneous likelihood fits, and parametric/non-parametric bootstraps; visualisations and confidence bands.  
  <span class="muted"><a href="https://github.com/barongracias/S1-Fitting-Coursework">github.com/barongracias/S1-Fitting-Coursework</a></span>  
- **5D interpolation platform (FastAPI + Next.js)** - full-stack app for 5D->1D regression with NumPy and TensorFlow backends, file uploads, artifact tracking, and docs; Docker/local scripts and synthetic data packages.  
  <span class="muted"><a href="https://github.com/barongracias/InterPyApp">github.com/barongracias/InterPyApp</a> · <a href="/projects/interpyapp/">Case study</a></span>  
- **Handwritten digit ML suite with triplet embeddings** - Optuna-tuned MLP classifier with determinism checks, MNIST transfer study, custom triplet loss, and a 2D CIFAR-10 embedding compared against t-SNE.  
  <span class="muted"><a href="https://github.com/barongracias/m1-machine-learning">github.com/barongracias/m1-machine-learning</a> · <a href="/projects/m1-machine-learning/">Case study</a></span>

[Want details or a walk-through? Email me.](mailto:barongracias@gmail.com){: .btn .btn--primary }
