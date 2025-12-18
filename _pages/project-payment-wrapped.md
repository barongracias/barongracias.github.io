---
title: "Open Banking \"Payment Wrapped\""
permalink: /projects/payment-wrapped/
layout: single
author_profile: true
---

A pair of modules that classify payment categories and surface Spotify Wrapped-style insights to users, driving engagement for an Open Banking product.

## What I built
- Category mapping model that turns raw transaction text into intuitive labels.  
- Payment statistics module that summarises spend patterns, merchants, and habits over time.  
- A/B test design and analysis to validate user value.

## Problem
Users struggled to see how their payment behaviour changed over time. The product needed sticky insights and better categorisation to increase satisfaction and retention.

## Approach
1) Cleaned and tokenised payment references; built fuzzy-matching heuristics to normalise merchants.  
2) Trained classification models for category assignment, with rules for edge cases and long-tail entities.  
3) Designed the Wrapped experience: time-bound summaries, top merchants, streaks, and anomalies.  
4) Ran A/B tests, measuring satisfaction, repeat opens, and downstream feature adoption.

## Impact
- 80%+ user satisfaction in experiments and a clearer retention hook for the product.  
- Reduced manual clean-up for customer support by improving category accuracy.

## Stack
Python, scikit-learn, pandas, SQL, experiment design and analysis tooling, lightweight API integration.
