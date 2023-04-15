---
layout: page
permalink: /publications/
title: publications 🗞️
description: #
years: [2023, 2022, 2020, 2019, 2018]
nav: true
nav_order: 1
---
<!-- _pages/publications.md -->
<div class="publications">

<h2 class="year">Manuscripts</h2>
{% bibliography -f manuscripts --group_by year --group_order descending %}

<h2 class="year">Journal articles</h2>
{% bibliography -f papers --group_by year --group_order descending %}

<h2 class="year">Proceedings articles</h2>
{% bibliography -f proceedings --group_by year --group_order descending %}

<h2 class="year">Theses</h2>
{% bibliography -f theses --group_by year --group_order descending %}
</div>