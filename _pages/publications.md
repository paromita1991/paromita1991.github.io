---
layout: page
permalink: /publications/
title: Publications
description:  
years: [2025,2024,2023, 2022, 2021, 2020, 2019, 2015]
nav: true
nav_order: 3
---
<!-- _pages/publications.md -->
<style>
  .publications { max-width: 900px; }

  .pub-year {
    margin-top: 2rem;
    margin-bottom: 0.75rem;
    padding-top: 1rem;
    border-top: 1px solid #eee;
    font-weight: 650;
    letter-spacing: 0.2px;
  }

  /* Optional: slightly tighter bib spacing (works with many Jekyll Scholar themes) */
  .publications .bibliography li { margin-bottom: 0.75rem; }
</style>

<div class="publications">
  {%- for y in page.years -%}
    <h2 id="y{{ y }}" class="pub-year">{{ y }}</h2>
    {% bibliography -q @*[year={{ y }}]* %}
  {%- endfor -%}
</div>
