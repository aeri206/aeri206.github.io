---
layout: page
permalink: /publications
title: publications
years: [2025, 2024, 2023, 2022]
nav: true
nav_order: 1
---
<!-- _pages/publications.md -->
<div class="publications">

<h2 class="bibliography">Visualization</h2>
{% bibliography -f {{ site.scholar.bibliography }} -q @*[abbr=IEEE TVCG] || @*[abbr=IEEE PacificVis] || @*[abbr=IEEE TPAMI] || @*[abbr=IEEE VIS] %}

<h2 class="bibliography">Other Publications</h2>
{% bibliography -f {{ site.scholar.bibliography }} -q @*[abbr=JMIR] || @*[abbr=Health] %}

</div>
