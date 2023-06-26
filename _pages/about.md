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
My research interest lies in 3D sensing. I deliver algorithms in estimating intrinsic, correspondence, depth, and pose from few images.


I am on track to graduate in Winter 2023 and am actively seeking full-time employment opportunities!


<div class="publications">
{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f {{ site.scholar.bibliography }} -q @*[year={{y}}]* %}
{% endfor %}
</div>