---
layout: single
classes: wide
title: "Fangtong Zhou"
permalink: /
author_profile: true
toc: false
---

## About {#about}
Hi! I’m **Fangtong Zhou**, a Ph.D. student at **Wireless@VT, Virginia Tech**.  
My research focuses on **Federated Learning** (semi-asynchronous, split, hybrid) and **wireless/edge AI systems**.  
I’m broadly interested in efficient distributed optimization and reliable learning over wireless networks.

---

## Education {#education}
- **Ph.D.** in Electrical and Computer Engineering, *Virginia Tech*, 20XX–present  
- **M.S.** in Electrical and Computer Engineering, *ShanghaiTech University*, 20XX  
- **B.S.** in Electrical Engineering, *Shanghai University*, 20XX

---

## News {#news}
- 2025-09 — Website launched 🎉  
- 2025-08 — Paper submitted on semi-asynchronous FL over dynamic wireless networks

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
**Conference Reviewer:** NeurIPS, ICML, ICLR, AISTATS, IEEE INFOCOM  
**Journal Reviewer:** IEEE TCOM, IEEE TWC, TMC, IoT-J, TMLR

---

## Teaching {#teaching}
<ul>
{% assign teach = site.teaching | sort: "date" | reverse %}
{% for t in teach %}
  <li>
    <strong>{{ t.title }}</strong> — {{ t.institution }}{% if t.semester %}, {{ t.semester }}{% endif %}{% if t.date %} ({{ t.date | date: "%Y" }}){% endif %}
  </li>
{% endfor %}
</ul>
