---
layout: single
classes: wide
title: "Fangtong Zhou"
permalink: /
author_profile: true
toc: false
show_title: false
---

## About
Hello and welcome! I am currently a second-year Ph.D. student at **Virginia Tech**, majoring in Computer Engineering, advised by [Prof. Tom Hou](https://www.cnsr.ictas.vt.edu/THou.html). 
Previous to that, I obtained my master’s degree in Information Engineering at **ShanghaiTech University** under the supervision of [Prof. Yong Zhou](https://faculty.sist.shanghaitech.edu.cn/faculty/zhouyong/) and [Prof. Yang Yang](https://facultyprofiles.hkust-gz.edu.cn/faculty-personal-page/YANG-Yang/yyiot), and my bachelor's degree in Information Engineering at **South China University of Technology**.
My research focuses on **Wireless Federated Learning**. I’m broadly interested in efficient distributed optimization and reliable learning over wireless networks.

---

## Education :mortar_board: {#education}
- **Ph.D.** in Computer Engineering, *Virginia Tech*, 2024. Fall--present  
- **M.S.** in Information Engineering, *ShanghaiTech University*, 2021--2024  
- **B.S.** in Information Engineerin, *South China University of Technology*, 2017--2024

---

## News {#news}
- 2025-08 -- One paper was accepted by IEEE MILCOM. :tada:
- 2025-07 —- One paper was submitted to IEEE INFOCOM.
- 2024-08 —- I started my Ph.D. journey in the ECE department at Virginia Tech, Go Hokies!

---

## Publications {#publications}
<ul>
{% assign pubs = site.publications | sort: "date" | reverse %}
{% for p in pubs %}
  <li>
    <strong>{{ p.title }}</strong>{% if p.venue %}, <em>{{ p.venue }}</em>{% endif %}{% if p.date %} ({{ p.date | date: "%Y" }}){% endif %}.
    {% if p.paperurl %} <a href="{{ p.paperurl }}" target="_blank">paper</a>{% endif %}
    {% if p.code %} <a href="{{ p.code }}" target="_blank">code</a>{% endif %}
    {% if p.slides %} <a href="{{ p.slides }}" target="_blank">slides</a>{% endif %}
  </li>
{% endfor %}
</ul>

---

## Review and Service {#service}
**Conference Reviewer:** IEEE ICC, IEEE GlobeCom, IEEE VTC
**Journal Reviewer:** IEEE TWC, IEEE TVT, IEEE TGCN

---

## Teaching {#teaching}
- **Graduate Teaching Assistant** —- *ECE 2704 Signals and Systems*, Virginia Tech, Fall 2024 & Spring 2025
- **Teaching Assistant** — *CS 287 Network Intelligence*, ShanghaiTech University, Fall 2022 

