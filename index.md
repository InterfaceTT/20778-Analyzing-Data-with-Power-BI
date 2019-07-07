---
title: Online Hosted Instructions
permalink: index.html
layout: home
---

# Content Directory

Hyperlinks to each of the lab exercises and demos are listed below.

## Presentation

[Module 2 Slides]{https://interfacett.github.io/20778-Analyzing-Data-with-Power-BI/Presentation/20778C_02U.pdf}

## Labs

{% assign labs = site.pages | where_exp:"page", "page.url contains '/Instructions/'" %}
| Module | Lab |
| --- | --- | 
{% for activity in labs  %}| {{ activity.lab.module }} | [{{ activity.lab.title }}{% if activity.lab.type %} - {{ activity.lab.type }}{% endif %}]({{ site.github.url }}{{ activity.url }}) |
{% endfor %}
