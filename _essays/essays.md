---
layout: page
title: Essays
permalink: /essays/
---

# Essays

<ul>
  {% for essay in site.essays %}
    <li><a href="{{ essay.url }}">{{ essay.title }}</a></li>
  {% endfor %}
</ul>
