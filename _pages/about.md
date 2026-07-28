---
layout: page
title:
permalink: /
years: [2026, 2024, 2023, 2020]
nav: false
nav_order: 0
fontawesome_css: https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css
---

<div style="float: right; margin-left: 20px; text-align: center; margin-top: 10px;">
  <img src="/assets/img/shngjz_selfie.jpg" alt="Shengjie Zhu" style="width: 180px; height: 200px; object-fit: cover;">
</div>

<font size="6.5"> Biography </font>
Shengjie Zhu is an Applied Scientist at Amazon Ring AI team. 
His expertise lies in Spatial AI systems: designing customer-facing agentic front-ends grounded in a 3D-vision backend spanning camera calibration, localization, reconstruction, and Structure-from-Motion.
He earned his Ph.D. from Michigan State University under the supervision of Professor [Xiaoming Liu](http://www.cse.msu.edu/~liuxm/index2.html).
His doctoral thesis focuses on recovering 3D structure and motion from image collections.

<span style="margin-right: 20px">[<i class="fas fa-file-pdf"></i> Resume](https://shngjz.github.io/assets/pdf/Shengjie_Zhu_Resume.pdf)</span>
<span style="margin-right: 20px">[<i class="fas fa-graduation-cap"></i> Google Scholar](https://scholar.google.com/citations?user=4hHEXZkAAAAJ&hl=en)</span>
<span style="margin-right: 20px">[<i class="fab fa-linkedin"></i> Linkedin](https://www.linkedin.com/in/shengjie-zhu-b71945159/)</span>
<span style="margin-right: 20px">[<i class="fab fa-github"></i> Github](https://github.com/ShngJZ)</span>

<div class="publications">
{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f {{ site.scholar.bibliography }} -q @*[year={{y}}]* %}
{% endfor %}
</div>
