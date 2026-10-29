---
layout: page
title: Multidimensional Projection
description: Making projections of high-dimensional data explainable, reliable, and explorable.
img: assets/img/publication_preview/towards2025cho.png
importance: 1
category: research
papers: [cho2025towards, jeon2023zadu, jeon2025measuring]
---

Multidimensional projection (MDP), also called dimensionality reduction, maps high-dimensional data onto a 2D scatterplot. Projections are widely used, but the patterns they show are hard to trust and hard to relate back to the original features.
My work asks how analysts can **explore** projections interactively, **evaluate** how faithful they are, and **explain** which features shape them.

## Research

<div class="publications">
{%- for key in page.papers -%}
  {% bibliography -f {{ site.scholar.bibliography }} -q @*[key={{ key }}] %}
{%- endfor -%}
</div>

## Interactive Demos

- **[Projection Explorer](https://aericho.com/mdp-tour/)** — Tours through projections of benchmark datasets, animating between embeddings and highlighting clusters.
- **[Metric Viewer for MDP](https://aericho.com/metric_viewer/)** — Linked histograms of projection quality metrics (Trustworthiness, Continuity, Steadiness, Cohesiveness, DTM, …). Brush a metric range to filter projections by method.
- **[Projection Matrix](https://aericho.com/mdp-matrix/)** — Matrix visualization comparing many projections of the same data, with seriation ([reorder.js](https://github.com/jdfekete/reorder.js/)), sorting by hyperparameters, and an adjustable similarity threshold.
- **[Projection Comparison Study](https://aericho.com/mdp_pilot/)** — Pilot study interface for comparing and ranking multiple projections side by side.

## Code & Datasets

- **[ZADU](https://github.com/hj-n/zadu)** — Python library of distortion measures for evaluating the reliability of dimensionality reduction embeddings.
- **[Labeled Datasets](https://github.com/hj-n/labeled-datasets)** — 96 benchmark datasets for external clustering validation, with class-label matching scores ([project page](https://hyeonword.com/clm-home/)).
