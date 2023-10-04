---
layout: page
title:  
permalink: /
years: [2023, 2020]
nav: false
nav_order: 0
---
<font size="6.5"> About Me </font>
I am Shengjie Zhu, currently pursuing a Ph.D. at Michigan State University under the supervision of Dr. Xiaoming Liu. In 2017, I completed my B.E. degree at SouthEast University. 
My research focuses on 3D perception, including intrinsic, correspondence, depth, and pose estimation from a few neighboring frames.

I am on track to graduate in Winter 2023 and am actively seeking full-time employment opportunities!


<div class="publications">
{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f {{ site.scholar.bibliography }} -q @*[year={{y}}]* %}
{% endfor %}
</div>