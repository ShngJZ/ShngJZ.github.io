---
layout: about
title: about
permalink: /
subtitle: Applied Scientist &middot; Ring AI, Amazon
years: [2026, 2024, 2023, 2020]
nav: false
nav_order: 0
profile:
  align: right
  image: shngjz_selfie.jpg
  image_circular: false
news: false
selected_papers: false
social: false
---

Shengjie Zhu is an Applied Scientist at Amazon Ring AI team.
His expertise lies in Spatial AI systems: designing customer-facing agentic front-ends grounded in a 3D-vision backend spanning camera calibration, localization, reconstruction, and Structure-from-Motion.
He earned his Ph.D. from Michigan State University under the supervision of Professor [Xiaoming Liu](http://www.cse.msu.edu/~liuxm/index2.html).
His doctoral thesis focuses on recovering 3D structure and motion from image collections.

<div class="contact-links mt-3 mb-4">
  <a class="btn btn-sm z-depth-0 mr-2" href="https://shngjz.github.io/assets/pdf/Shengjie_Zhu_Resume.pdf" role="button"><i class="fas fa-file-pdf"></i>&nbsp;Resume</a>
  <a class="btn btn-sm z-depth-0 mr-2" href="https://scholar.google.com/citations?user=4hHEXZkAAAAJ&hl=en" role="button"><i class="fas fa-graduation-cap"></i>&nbsp;Google Scholar</a>
  <a class="btn btn-sm z-depth-0 mr-2" href="https://www.linkedin.com/in/shengjie-zhu-b71945159/" role="button"><i class="fab fa-linkedin"></i>&nbsp;LinkedIn</a>
  <a class="btn btn-sm z-depth-0" href="https://github.com/ShngJZ" role="button"><i class="fab fa-github"></i>&nbsp;GitHub</a>
</div>

<hr class="bio-pub-divider">

<div class="publications">
{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f {{ site.scholar.bibliography }} -q @*[year={{y}}]* %}
{% endfor %}
</div>
