---
layout: page
permalink: /publications/
title: publications 🗞️
description: #
years: [2019]
nav: true
nav_order: 1
---
<!-- _pages/publications.md -->
<div class="publications">


### Published papers
{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography --query @article[keywords != Proceedings] %}
{% endfor %}

</div>
