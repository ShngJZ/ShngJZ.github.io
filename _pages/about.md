---
layout: page
title:  
permalink: /
years: [2024, 2023, 2020]
nav: false
nav_order: 0
---
<font size="6.5"> About Me </font>
My name is Shengjie Zhu, a Ph.D. student at Michigan State University supervised by Dr. Xiaoming Liu.
My research focuses on monocular/multi-view depth estimation. This is a comprehensive task, encompassing topics including
NeRF, structure-from-motion, correspondence estimation, camera pose estimation, camera calibration, self-supervision, etc.

[[Resume](https://shngjz.github.io/assets/pdf/Shengjie_Zhu_Resume.pdf)] [[Google Scholar](https://scholar.google.com/citations?user=4hHEXZkAAAAJ&hl=en)] [[Linkedin](https://www.linkedin.com/in/shengjie-zhu-b71945159/)] [[Github](https://github.com/ShngJZ)] 

<div class="publications">
{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f {{ site.scholar.bibliography }} -q @*[year={{y}}]* %}
{% endfor %}
</div>