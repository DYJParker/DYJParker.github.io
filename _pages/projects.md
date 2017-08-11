---
layout: archive
permalink: /projects/
title: Android Projects
header:
#  overlay_image: /assets/images/carli-jeen-430.jpg
  overlay_color: 'match'
---

<div class="grid__wrapper">
  {% for post in site.projects %}
    {% include archive-single.html type="grid" %}
  {% endfor %}
</div>