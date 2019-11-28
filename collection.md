---
layout: wrapper
title: collection
permalink: /collection/
---

{% for tool in site.tools %}
 <div class="tool">
  <h2><a href="{{ tool.url }}">{{ tool.title }}</a></h2>
</div>
{% endfor %}
