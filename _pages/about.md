---
layout: page
title:  
permalink: /
years: [2024, 2023, 2020]
nav: false
nav_order: 0
---
<font size="6.5"> Biography </font>
I am Shengjie Zhu, an Applied Scientist at Amazon.
I earned my Ph.D. at Michigan State University supervised by Professor Xiaoming Liu. 
My primary research interests lie in 3D Vision, encompassing monocular / multi-view depth estimation, camera calibration, image correspondence estimation, and two-view / multi-view camera pose estimation.

[[Resume](https://shngjz.github.io/assets/pdf/Shengjie_Zhu_Resume.pdf)] [[Google Scholar](https://scholar.google.com/citations?user=4hHEXZkAAAAJ&hl=en)] [[Linkedin](https://www.linkedin.com/in/shengjie-zhu-b71945159/)] [[Github](https://github.com/ShngJZ)] 

<div class="publications">
{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f {{ site.scholar.bibliography }} -q @*[year={{y}}]* %}
{% endfor %}
</div>