---
layout: single
classes: wide
permalink: /
author_profile: true
toc: false
---

## About :smile:
Hello and welcome! I am currently a second-year Ph.D. student at **Virginia Tech**, Blacksburg, VA, USA, majoring in Computer Engineering, advised by [Prof. Tom Hou](https://www.cnsr.ictas.vt.edu/THou.html). 
Previous to that, I obtained my master’s degree in Information Engineering at **ShanghaiTech University**, Shanghai, China, under the supervision of [Prof. Yong Zhou](https://faculty.sist.shanghaitech.edu.cn/faculty/zhouyong/) and [Prof. Yang Yang](https://facultyprofiles.hkust-gz.edu.cn/faculty-personal-page/YANG-Yang/yyiot), and my bachelor's degree in Information Engineering at **South China University of Technology**, Guangzhou, Guangdong, China.
My research focuses on wireless federated learning.

---

## Education :mortar_board: {#education}
- **Ph.D.** in Computer Engineering, *Virginia Tech*, 2024. Fall--present  
- **M.S.** in Information Engineering, *ShanghaiTech University*, 2021--2024  
- **B.E.** in Information Engineerin, *South China University of Technology*, 2017--2021

---

## News {#news}
- 2025-08 - One paper was accepted by IEEE MILCOM. :tada:
- 2025-07 - One paper was submitted to IEEE INFOCOM.
- 2024-08 - I started my Ph.D. journey in the ECE department at Virginia Tech, Go Hokies!

---

## Publications :file_folder: {#publications}
<ul>
{% assign pubs = site.publications | sort: "date" | reverse %}
{% for p in pubs %}
  <li>
    {{ p.authors | markdownify | strip_newlines | remove: '<p>' | remove: '</p>' }}, “{{ p.title }},”
    {% if p.journal %}
      <em>{{ p.journal }}</em>{% if p.volume %}, vol. {{ p.volume }}{% endif %}{% if p.number %}, no. {{ p.number }}{% endif %}{% if p.pages %}, pp. {{ p.pages }}{% endif %}{% if p.month %}, {{ p.month }}{% endif %}{% if p.year %}{{ p.year }}{% endif %}
    {% else %}
      <em>{{ p.venue }}</em>{% if p.address %}, {{ p.address }}{% endif %}{% if p.month %}, {{ p.month }}{% endif %}{% if p.year %}, {{ p.year }}{% endif %}
    {% endif %}.
    {% if p.paperurl %} <a href="{{ p.paperurl }}" target="_blank">paper</a>{% endif %}
    {% if p.code %} <a href="{{ p.code }}" target="_blank">code</a>{% endif %}
    {% if p.slides %} <a href="{{ p.slides }}" target="_blank">slides</a>{% endif %}
  </li>
{% endfor %}
</ul>


---

## Review and Service {#service}
- **Conference Reviewer:** IEEE ICC, IEEE GlobeCom, IEEE VTC
- **Journal Reviewer:** IEEE TWC, IEEE TVT, IEEE TGCN

---

## Teaching {#teaching}
- **Graduate Teaching Assistant:**  *ECE 2704 Signals and Systems*, Virginia Tech, Fall 2024 & Spring 2025
- **Graduate Teaching Assistant:**  *CS 287 Network Intelligence*, ShanghaiTech University, Fall 2022 

