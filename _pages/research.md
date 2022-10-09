---
layout: page
permalink: /publications/
title: Research
description: 
years: [2022]
nav: true
nav_order: 1
---
<!-- _pages/publications.md -->
<div class="publications" >


  <!-- {% bibliography -f papers -q @*[year={{y}}]* %} -->
  


{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers   %}
{% endfor %}

</div>
