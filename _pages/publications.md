---
layout: page
permalink: /publications/
title: publications
description:
years: [2024]
nav: true
nav_order: 1
---
<!-- _pages/publications.md -->

<h2>First author</h2>   
<div class="publications custom-font">

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>
