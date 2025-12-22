---
title: "g-maps-timeline - Fog-of-war travel map"
permalink: /projects/g-maps-timeline/
layout: single
author_profile: true
---

Turns Google Maps Timeline exports into an RPG-style map with aggregated tiles so you can explore travel history without exposing raw traces.

## What I built
- Streaming ingest that parses Google Timeline JSON/KML, dedupes points, and buckets visits by year.
- H3 aggregation and tile generation to keep locations fuzzy (privacy-first) while still showing coverage and intensity.
- MapLibre frontend with fog-of-war styling, year filters, and hover tooltips for quick exploration.
- Packaging for local/offline use: CLI, Docker setup, and reproducible scripts so data never leaves your machine.

## Problem
Raw Timeline exports are noisy, huge, and too precise to share safely. I needed a way to visualize multi-year travel without leaking exact coordinates or spending hours cleaning files.

## Approach
1) Normalised Timeline exports into a consistent schema; removed jitter/duplicate points and grouped traces by trip/stop.  
2) Applied H3 binning at configurable resolutions to obscure exact positions while preserving geographic patterns.  
3) Generated MapLibre tiles per year with style metadata (fog overlays, intensity ramps) to keep rendering fast even with large histories.  
4) Built a Next.js/MapLibre viewer that loads local tiles, supports year toggles, and can be hosted statically.  
5) Wrapped ingestion and tile generation in CLI/Docker scripts so the pipeline is repeatable without manual GIS work.

## Impact
- Private-by-default maps: shareable tiles without leaking raw lat/longs.  
- Faster exploration: filtered, deduped data renders quickly even for multi-year exports.  
- Reusable pipeline: point it at new Timeline exports and regenerate tiles with one command.

## Stack
Python, H3, MapLibre, Next.js, CLI/Docker scripts, GitHub Actions for linting/build.

<a class="btn btn--primary" href="https://github.com/barongracias/FogofWar">View repo</a>
