---
layout: page
permalink: /talks/
title: talks 🎤
description: #
years: [2022, 2019, 2018]
nav: true
nav_order: 1
---
<!-- _pages/talks.md -->
<div class="publications">

Invited talks

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f talks -q @*[year={{y}}]* %}
{% endfor %}

Other talks

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f talks -q @*[year={{y}}]* %}
{% endfor %}

</div>
