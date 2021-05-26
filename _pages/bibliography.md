---
layout: page
permalink: /bibliography/
title: publications
description: Some of my research works.
years: [2021, 2020, 2019]
nav: true
---
<div class="publications">
  {% for y in page.years %}
   <h2 class ="year">{{y}}</h2>
   {% bibliography -f papers -q @*[year={{y}}]* %}{% endfor %}
</div>
