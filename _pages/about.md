
---
layout: home
title: "Fangtong Zhou"
permalink: /
author_profile: true
---


<!-- 1. Intro -->
## About {#about}
Hi! I’m **Fangtong Zhou**, a Ph.D. student at **Wireless@VT, Virginia Tech**.  
My research focuses on **Federated Learning** (semi-asynchronous, split, hybrid) and **wireless/edge AI systems**.  
I’m broadly interested in efficient distributed optimization and reliable learning over wireless networks.

---

<!-- 2. Education -->
## Education {#education}
- **Ph.D.** in Electrical and Computer Engineering, *Virginia Tech*, 20XX–present  
- **M.S.** in Electrical and Computer Engineering, *ShanghaiTech University*, 20XX  
- **B.S.** in Electrical Engineering, *Shanghai University*, 20XX

---

<!-- 3. News -->
## News {#news}
- 2025-09 — Website launched 🎉  
- 2025-08 — Paper submitted on semi-asynchronous FL over dynamic wireless networks  
*(Add more in `_news/` later if你想做独立新闻页)*

---

<!-- 4. Publications -->
## Publications {#publications}
<!-- 方式A：从 _publications/ 集合自动列出（推荐） -->
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

<!-- 若暂时没有 _publications/ 内容，可先用“方式B：手写列表”，把上面循环删掉，改成如下示例：
- **Paper title**. *Venue*, 2025. [paper](#) [code](#)
-->

---

<!-- 5. Review & Service -->
## Review and Service {#service}
**Conference Reviewer:** NeurIPS, ICML, ICLR, AISTATS, IEEE INFOCOM  
**Journal Reviewer:** IEEE TCOM, IEEE TWC, TMC, IoT-J, TMLR  
*(按你的实际改即可；也可以把内容搬到 `_pages/misc.md` 并在此只放一个简介)*

---

<!-- 6. Teaching -->
## Teaching {#teaching}
<ul>
{% assign teach = site.teaching | sort: "date" | reverse %}
{% for t in teach %}
  <li>
    <strong>{{ t.title }}</strong> — {{ t.institution }}{% if t.semester %}, {{ t.semester }}{% endif %}{% if t.date %} ({{ t.date | date: "%Y" }}){% endif %}
  </li>
{% endfor %}
</ul>

<!-- 也可以先手写：
- Teaching Assistant — Optimization for ML, Virginia Tech (Fall 2024)
-->
