---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======

**Tsinghua University**, Beijing  
Ph.D. in Building Technology Science, 2023–present  

**Harbin Institute of Technology**, Harbin  
B.Arch. in Architecture, 2018–2023  
B.Eng. in Artificial Intelligence, 2019–2022  

---

Technical Skills
======

**Building Performance & Simulation**  
Rhino & Grasshopper, Revit, Ladybug, EnergyPlus, DesignBuilder  

**Programming & Modeling**  
Python, R  

---

Academic Service
======

- Member, Technical Committee (JTC-20), International Commission on Illumination (CIE)  
- Lead, Architecture + Artificial Intelligence Research Group, Future Society  
- Reviewer: *Journal of Building Engineering*, *Renewable Energy*  

---

Publications
======

<ul>
{% for post in site.publications reversed %}
  {% include archive-single-cv.html %}
{% endfor %}
</ul>
