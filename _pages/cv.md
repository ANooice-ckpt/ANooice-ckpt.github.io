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

/* 统一正文风格 */
#main {
  font-size: 0.95rem;
  line-height: 1.6;
}

/* 所有列表统一缩进 */
#main ul {
  margin-left: 1.2em;
  margin-bottom: 1em;
}

/* 列表项间距 */
#main li {
  margin-bottom: 0.5em;
}

/* 链接继承颜色（适配夜间模式） */
#main a {
  color: inherit;
  text-decoration: none;
}

#main a:hover {
  text-decoration: underline;
}

/* 标题大小控制 */
#main h2 {
  font-size: 1.4rem;
  margin-top: 1.5em;
  margin-bottom: 0.6em;
}

</style>

---

## Education

- Ph.D. in Building Technology Science, Tsinghua University, 2023–present  
- B.Arch. in Architecture, Harbin Institute of Technology, 2018–2023  
- B.Eng. in Artificial Intelligence, Harbin Institute of Technology, 2019–2022  

---

## Academic Service

- Member, Technical Committee (JTC-20), International Commission on Illumination (CIE)  
- Lead, Architecture + Artificial Intelligence Research Group, Future Society  
- Reviewer: *Journal of Building Engineering*, *Renewable Energy*  

---

## Publications

<ul>
{% for post in site.publications reversed %}
  <li>
    <a href="{{ post.doi }}" target="_blank">
      {{ post.title }}
    </a><br>
    {{ post.authors }}<br>
    {{ post.venue }} · {{ post.year }}
  </li>
{% endfor %}
</ul>
