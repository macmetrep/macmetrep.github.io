---
layout: page
title: Guides
permalink: /guides/
---

# Available Guides

{% for guide in site.pages %}
  {% if guide.path contains 'guides/' and guide.name != 'index.md' %}
* [{{ guide.title | default: guide.name | remove: '.md' | titleize }}]({{ guide.url | relative_url }})
  {% endif %}
{% endfor %} 