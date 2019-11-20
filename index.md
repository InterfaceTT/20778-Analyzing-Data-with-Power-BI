---
title: Online Hosted Instructions
permalink: index.html
layout: home
---

# Content Directory

Hyperlinks to each of the lab exercises and demo instructions are listed below.

## Labs

{% assign labs = site.pages | where_exp:"page", "page.url contains '/Instructions/'" %}
| **Module Lab** | **Link** |
| --- | --- | 
{% for activity in labs  %}| {{ activity.lab.module }} | [{{ activity.lab.title }}{% if activity.lab.type %} - {{ activity.lab.type }}{% endif %}]({{ site.github.url }}{{ activity.url }}) |
{% endfor %}

## Demonstrations

{% assign labs = site.pages | where_exp:"page", "page.url contains '/Demonstrations/'" %}
| **Module Demo** | **Link** |
| --- | --- | 
{% for activity in labs  %}| {{ activity.lab.module }} | [{{ activity.lab.title }}{% if activity.lab.type %} - {{ activity.lab.type }}{% endif %}]({{ site.github.url }}{{ activity.url }}) |
{% endfor %}