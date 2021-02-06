---
layout: demo
title: Rising Sun
---

# {{page.title}}

Show the time: {{ site.when }}

Data file contents:

{% for item in site.data.demo %}


{{ site.data.demo }}

{% endfor %}