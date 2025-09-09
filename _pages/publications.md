---
layout: page
permalink: /publications/
title: publications 🗞️
description: If a pdf isn't linked, just ask me! #
nav: true
nav_order: 1
---
<!-- _pages/publications.md -->
<div class="publications">

<h2 class="year">Dissertation</h2><br><br>
{% bibliography -f dissertation %}

<h2 class="year">Journal articles</h2><br><br>
{% bibliography -f papers %}

<h2 class="year">Proceedings articles</h2><br><br>
{% bibliography -f proceedings %}

<h2 class="year">Older stuff</h2><br><br>
{% bibliography -f theses %}
</div>