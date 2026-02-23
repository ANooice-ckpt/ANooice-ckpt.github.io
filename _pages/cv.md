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
.archive__item-title a {
  color: inherit !important;
  text-decoration: none !important;
}

.archive__item-title a:hover {
  text-decoration: underline !important;
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
