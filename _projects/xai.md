---
layout: page
title: Explainable AI
description: Interactive visual explanations that make model behavior understandable.
img: assets/img/publication_preview/cho2025lime.png
importance: 2
category: research
papers: [cho2025lime, cho2025towards]
---

Explanation methods such as LIME and SHAP are widely used, but their outputs are often taken at face value without understanding how they are computed or how to read them.
I build interactive visualizations that let people see **how** explanations are produced and **what** they actually say about a model.

## Research

<div class="publications">
{%- for key in page.papers -%}
  {% bibliography -f {{ site.scholar.bibliography }} -q @*[key={{ key }}] %}
{%- endfor -%}
</div>

## Interactive Demos

- **[LIME & SHAP Explained](https://aericho.com/explaining-explainable-ml/)** — An interactive visual guide that walks through how LIME and SHAP compute local explanations, step by step, and how to interpret the results (VISxAI 2025).
