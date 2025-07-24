---
layout: page
title: Essays
permalink: /essays/
published: false
---

# Essays

<ul>
  {% for essay in site.essays %}
    <li><a href="{{ essay.url }}">{{ essay.title }}</a></li>
  {% endfor %}
</ul>
