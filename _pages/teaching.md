---
title: Teaching
---
{% for course in site.teaching %}
  <h2>{{ course.name }} - {{ course.semester }}</h2>
  <p>{{ course.content | markdownify }}</p>
{% endfor %}
