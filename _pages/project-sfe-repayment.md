---
title: "SFE repayment simulator"
permalink: /projects/sfe-repayment/
layout: single
author_profile: true
---

Next.js tool that models Student Finance England loans (Plans 1/2/5 + PGL), lets users adjust salaries/interest assumptions, and visualises payoff timelines.

## What I built
- Repayment engine that mirrors SFE rules (thresholds, tapering, interest bands, plan combinations, PG loans).
- Interactive UI for salary timelines, overpayments, interest assumptions, and scenario comparisons with charts/tables.
- Export/print views to share plans with advisers or keep records.
- CI and linting to keep the calculations deterministic as rules change.

## Problem
Borrowers struggle to understand how changing salaries, thresholds, or overpayments affect payoff dates across multiple SFE plans. Existing calculators were opaque or out of date.

## Approach
1) Codified official repayment formulas for Plans 1/2/5 and PGL, including dynamic thresholds and interest bands.  
2) Built a deterministic calculation layer with tests to guard against regressions when rules update.  
3) Designed a Next.js UI with sliders/inputs for income trajectories and overpayments, updating charts in real time.  
4) Added scenario exports and printable summaries to make sharing easy.  
5) Containerised and scripted the app for quick local runs and deployment.

## Impact
- Clearer planning: users can see payoff dates and totals under different salary paths and overpayment strategies.  
- Maintainable rules engine: tests and typed configs make updating yearly thresholds straightforward.  
- Shareable outputs: exports reduce back-and-forth with advisers.

## Stack
Next.js/React, TypeScript, charting (e.g., Chart.js/Plotly), CSS modules, Jest/linting, Docker scripts.

<a class="btn btn--primary" href="https://github.com/barongracias/SFE-Repayment-Calculator">View repo</a>
