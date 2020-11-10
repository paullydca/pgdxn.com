---
title: pgdxn
subtitle: Gentleman of Adventure at <a href="https://www.beyondthepx.com" target="_blank" rel="noopener nofollow">Beyond the Pixel</a>. Has been helping brands stand out above the waves in a sea of ordinary for many years. 
layout: layouts/home.njk
---

<!-- Loop through collecton in /about folder -->
{%- for about in collections.about -%}
  {% include 'about-item.njk' %}
{%- endfor -%}
