---
layout: page
permalink: /people/
title: People
description: 
nav: true
nav_order: 4
---

<style>
  :root {
    --accent-purple: #6f42c1;
    --people-name: #222;
    --people-text: #444;
    --people-years: #666;
  }

  @media (prefers-color-scheme: dark) {
    :root {
      --accent-purple: #bfa7ff;
      --people-name: #ffffff;
      --people-text: #ffffff;
      --people-years: #9e9e9e;
    }
  }

  html[data-theme="dark"],
  html.dark,
  body.dark,
  body[data-theme="dark"] {
    --accent-purple: #bfa7ff;
    --people-name: #ffffff;
    --people-text: #ffffff;
    --people-years: #9e9e9e;
  }

  .people-section {
    max-width: 900px;
    margin-top: 1.5rem;
  }

  .people-heading {
    font-weight: 600;
    color: var(--accent-purple);
    font-size: 1.15rem;
    margin-bottom: 0.5rem;
  }

  .people-list {
    margin-left: 1rem;
    margin-bottom: 1.25rem;
  }

  .people-list li {
    margin-bottom: 0.4rem;
    color: var(--people-text) !important;
    opacity: 1 !important;
    line-height: 1.4;
  }

  .people-years {
    color: var(--people-years) !important;
    opacity: 1 !important;
    font-size: 0.9rem;
    margin-left: 0.25rem;
  }

  .people-list a {
    text-decoration: none;
    color: var(--people-name) !important;
    font-weight: 500;
    opacity: 1 !important;
  }

  .people-list a:hover {
    text-decoration: underline;
  }

  .people-list li em,
  .people-list li strong,
  .people-list li a {
    font-size: inherit;
    color: inherit;
    opacity: 1;
  }
</style>



<div class="people-section">

  <div class="people-heading">Current Students and Postdocs</div>
  <ul class="people-list">
    <li>
      <a href="https://jong-min.org/">Jongmin Mun</a>
      <span class="people-years">(2024–Present)</span>
    </li>
    <li>
      <a href="https://ao-sun.github.io/">Ao Sun</a>
      <span class="people-years">(2024–Present)</span>
    </li>
  </ul>

  <div class="people-heading">Alumni</div>
  <ul class="people-list">
    <li>
      <a href="https://www.marshall.usc.edu/personnel/minxing-zheng">Minxing Zheng</a>
      <span class="people-years">(2022–2024)</span>
    </li>
  </ul>

</div>
