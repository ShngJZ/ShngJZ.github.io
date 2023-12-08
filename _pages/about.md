---
layout: page
title:  
permalink: /
years: [2023, 2020]
nav: false
nav_order: 0
---
<font size="6.5"> About Me </font>
My name is Shengjie Zhu, a Ph.D. student at Michigan State University supervised by Dr. Xiaoming Liu. In 2017, I completed my B.E. degree at SouthEast University. 
My research focuses on 3D perception, including intrinsic, correspondence, depth, and pose estimation from a few neighboring frames.

I am on track to graduate in Winter 2023 and am actively seeking full-time employment opportunities!

[[Resume](https://drive.google.com/file/d/1LjS_QNgXtsIpSiFYRNOSYRatWLU34qOs/view?usp=drive_link)] [[Google Scholar](https://scholar.google.com/citations?user=4hHEXZkAAAAJ&hl=en)] [[Linkedin](https://www.linkedin.com/in/shengjie-zhu-b71945159/)] [[Github](https://github.com/ShngJZ)] 

<div class="publications">
{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f {{ site.scholar.bibliography }} -q @*[year={{y}}]* %}
{% endfor %}
</div>