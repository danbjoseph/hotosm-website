---
title: Projects
date: 2018-01-24 11:36:00 Z
permalink: "/projects/"
position: 3
layout: page
---

{% for item in site.projects %}
  <h2>{{ item.title }}</h2>
  <p>{{ item.description }}</p>
  <p><a href="{{ item.url }}">{{ item.title }}</a></p>
{% endfor %}