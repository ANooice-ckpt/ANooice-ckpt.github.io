---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<style>
/* 标题去粗体 */
.archive__item-title {
  font-weight: 400 !important;
  font-size: 0.95rem !important;
}

/* 标题链接继承颜色 */
.archive__item-title a {
  color: inherit !important;
  text-decoration: none !important;
}

.archive__item-title a:hover {
  text-decoration: underline !important;
}

/* 整个 publication 字号缩小 */
.archive__item {
  font-size: 0.95rem !important;
  margin-bottom: 0.6em !important;
}
</style>
Education
======

- Ph.D. in Building Technology Science, Tsinghua University, 2023–present  
- B.Arch. in Architecture, Harbin Institute of Technology, 2018–2023  
- B.Eng. in Artificial Intelligence, Harbin Institute of Technology, 2019–2022  

---

Academic Service
======

- Member, Technical Committee (JTC-20), International Commission on Illumination (CIE)  
- Lead, Architecture + Artificial Intelligence Research Group, Future Society  
- Reviewer: *Journal of Building Engineering*, *Renewable Energy*  

---

Publications
======

{% for post in site.publications reversed %}
  {% include archive-single-cv.html %}
{% endfor %}
