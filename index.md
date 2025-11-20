---
layout: default
title: "r00t_th3_h4rd_w4y"
description: "Hacking with HckCrk"
---

# Welcome to My Offensive Security Blog

I’m HckCrk — a creative professional turned cybersecurity practitioner. Here I share walkthroughs, research, and lessons learned in offensive security, red teaming, and penetration testing.

---

## Latest Posts

{% for post in site.blog %}
- [{{ post.title }}]({{ post.url }}) — <small>{{ post.date | date: "%Y-%m-%d" }}</small>
{% endfor %}
